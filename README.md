# 2FA-Solver

> A pure JavaScript Web Page to retrieve real-time OTP through a web page and generate/scan QR codes.
> > It can be used as an offline web page by downloading as it doesn't have any internet dependency.
> 
> Inspired and modify from [@nuintun](https://github.com/nuintun/) - [nuintun/qrcode](https://github.com/nuintun/qrcode) and [@russau](https://github.com/russau/) - [russau/ArduinoOTP](https://github.com/russau/ArduinoOTP)


### Contents
- [Overview](#overview)
- [2FA-Solver Web Page - Demo](#2fa-solver-web-page)
- [User Guide](#user-guide)
  - [QR Code (Image) Generator/Encoder](#qr-code-image-generatorencoder)
  - [QR Code (Image) Scanner/Decoder](#qr-code-Image-scannerdecoder)
  - [Retrieve One-Time Password in Real-Time](#retrieve-one-time-password-in-real-time)


### Overview

2FA Solver is a Javascript+HTML based web page that helps to generate/scan QR codes and retrieve One Time Password real-time using the secret key.

It can be used offline without any internet connection by downloading the [2FA-Solver.html](https://github.com/iamyuthan/2FA-Solver/blob/Master/2FA-Solver.html) file along with the [configs](https://github.com/iamyuthan/2FA-Solver/tree/Master/configs) folder and accessing it from the local machine. 
It can also be deployed on an online environment, as shown in the [2FA Solver](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html) site. However, generating/scanning QR codes and retrieving real-time OTP does not require an internet connection.


### 2FA-Solver Web Page

[2FA Solver](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

> [![image](https://user-images.githubusercontent.com/83505381/146655188-d981fdfd-2d93-4b1e-814f-7f036917708a.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)
> [![image](https://user-images.githubusercontent.com/83505381/146655222-f185a1cb-fd1e-433b-a7e6-34511aae2df9.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)
> [![image](https://user-images.githubusercontent.com/83505381/146655283-b23011c5-bc6a-4133-b36f-fd5127984ef6.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)


### User Guide

2FA Solver Web interface will consist of three main modules:
- [**QR Code (Image) Generator/Encoder**](#qr-code-image-generatorencoder) - *Encodes any content or the URL into a QR code Image.*
- [**QR Code (Image) Scanner/Decoder**](#qr-code-Image-scannerdecoder) - *Scans and extracts the content from a QR code image.*
- [**Retrieve One-Time Password in Real-Time**](#retrieve-one-time-password-in-real-time) - *Provides real-time OTP for a given secret key like google authenticator.*


#### QR Code (Image) Generator/Encoder

Provide the URL/content to encode as QR code in the text box (as highlighted below in red colour in the below screenshot).
> [![image](https://user-images.githubusercontent.com/83505381/146655317-76baef16-ffd1-4a7c-adbb-fc1e75d24b30.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

Select the appropriate settings required for your QR code image (as highlighted below in red colour in the below screenshot) and hit the **Generate** button. 
> [![image](https://user-images.githubusercontent.com/83505381/146655335-7bbdd3b2-cc04-4d16-8a42-9ad554798c35.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

The application will generate the QR code image which can be saved or copied by right-clicking from PC/MAC/Laptops or by long press on the image from phones.
> [![image](https://user-images.githubusercontent.com/83505381/146655366-8ede28ed-f596-40a6-92ac-d5c5d2742d25.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)



#### QR Code (Image) Scanner/Decoder

Click the **Choose File** button (as highlighted below in red colour in the below screenshot) to select the QR code image you want to scan/decode.
> [![image](https://user-images.githubusercontent.com/83505381/146655606-edf1317a-338a-49ab-bf87-919f0a4a627f.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

Hit the **Decode** button (as highlighted below in red colour in the below screenshot) to extract the content.
> [![image](https://user-images.githubusercontent.com/83505381/146655626-81bd4fcf-d37d-4eb5-839f-82ca29e2e6ce.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

You can copy the extracted secret key (as highlighted below in red colour in the below screenshot) for retrieving real-time OTP in the [Retrieve One-Time Password in Real-Time](#retrieve-one-time-password-in-real-time) tab.
> [![image](https://user-images.githubusercontent.com/83505381/146655678-327e6d9d-5f40-4a7e-9c0d-58173d9967f9.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)


#### Retrieve One-Time Password in Real-Time

Paste the secret key obtained from the [QR Code (Image) Scanner/Decoder](#qr-code-Image-scannerdecoder) tab (or the secret key you already have in hand) into the **Secret (base32)** text box (as highlighted below in red colour in the below screenshot).
> [![image](https://user-images.githubusercontent.com/83505381/146655795-14fb2b06-90eb-460e-895e-14b51d12a84d.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

The application will start displaying the OTP that belongs to the key in real-time, as shown below.
> [![image](https://user-images.githubusercontent.com/83505381/146655754-149536fb-5783-460e-be46-adb2fa0fb8dd.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

