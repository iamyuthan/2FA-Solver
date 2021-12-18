# 2FA-Solver

> A pure JavaScript Web Page to retrieve real-time OTP through a web page and generate/scan QR codes.
> > It can be used as an offline web page by downloading as it doesn't have any internet dependency.
> 
> Inspired and modify from [@nuintun](https://github.com/nuintun/) - [nuintun/qrcode](https://github.com/nuintun/qrcode) and [@russau](https://github.com/russau/) - [russau/ArduinoOTP](https://github.com/russau/ArduinoOTP)


### Contents
- [Overview](#overview)
- [2FA-Solver Web Page - Demo](#2fa-solver-web-page)
- [User Guide](#user-guide)
- - [QR Code (Image) Generator/Encoder](#qr-code-(Image)-generator/encoder)
- - [QR Code (Image) Scanner/Decoder](#qr-code-(Image)-scanner/decoder)
- - [Retrieve One-Time Password in Real-Time](#retrieve-one-time-password-in-real-time)


### Overview

2FA Solver is a Javascript+HTML based web page that helps to generate/scan QR codes and retrieve One Time Password real-time using the secret key.

It can be used offline without any internet connection by downloading the [2FA-Solver.html](https://github.com/iamyuthan/2FA-Solver/blob/Master/2FA-Solver.html) file along with the [configs](https://github.com/iamyuthan/2FA-Solver/tree/Master/configs) folder. 
Also, it can be deployed on an online environment as shown in the [2FA Solver](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html) site. However, generating/scanning QR codes and retrieving real-time OTP does not require an internet connection.


### 2FA-Solver Web Page

[2FA Solver](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)

[![image](https://user-images.githubusercontent.com/83505381/146654432-8ab01d77-3e49-4e88-beee-e915bdbef489.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)
[![image](https://user-images.githubusercontent.com/83505381/146654453-4a83c8e0-0b1d-4439-84e5-c76d62855a29.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)
[![image](https://user-images.githubusercontent.com/83505381/146654479-3cec2ab5-4c69-406f-8159-2869834c85bf.png)](https://iamyuthan.github.io/2FA-Solver/2FA-Solver.html)


### User Guide

2FA Solver Web interface will consist of three main modules:
- [**QR Code (Image) Generator/Encoder**](#qr-code-(Image)-generator/encoder) - *Encodes any content or the URL into a QR code Image.*
- [**QR Code (Image) Scanner/Decoder**](#qr-code-(Image)-scanner/decoder) - *Scans and extracts the content from a QR code image.*
- [**Retrieve One-Time Password in Real-Time**](#retrieve-one-time-password-in-real-time) - *Provides real-time OTP for a given secret key like google authenticator.*


#### QR Code (Image) Generator/Encoder

Provide the URL/content to encode as QR code in the text box (as highlighted below in red colour in the below screenshot).


Select the appropriate settings required for your QR code image (as highlighted below in red colour in the below screenshot) and hit the **Generate** button. It will generate the QR code image which can be saved or copied by right-clicking from PC/MAC/Laptops or by long press on the image from phones.


#### QR Code (Image) Scanner/Decoder

Click the **Choose File** button (as highlighted below in red colour in the below screenshot) to select the QR code image you want to scan/decode.


Hit the **Decode** button (as highlighted below in red colour in the below screenshot) to extract the content.


You can copy the extracted secret key (as highlighted below in red colour in the below screenshot) for retrieving real-time OTP in the [Retrieve One-Time Password in Real-Time](#retrieve-one-time-password-in-real-time) tab.



#### Retrieve One-Time Password in Real-Time

Paste the secret key obtained from the [QR Code (Image) Scanner/Decoder](#qr-code-(Image)-scanner/decoder) tab (or the secret key you already have in hand) into the **Secret (base32)** text box (as highlighted below in red colour in the below screenshot).


The application will start displaying the OTP that belongs to the key in real-time, as shown below.






