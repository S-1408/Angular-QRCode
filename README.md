# AngularQrcode
![Screenshot (6)](https://user-images.githubusercontent.com/60258353/95483066-a3c53000-0943-11eb-8a36-cea4090ea055.png)


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.2.

## Steps
step-1 install angular 2QR code module(npm install angular2-qrcode).
step-2 import QRModule in app module.
step-3 implement QRCode generator (<qr-code [value]="'www.positronx.io'"></qr-code>).


## QR Properties 
1. value = Takes a String value and convert String to QR Code,
2.size = sets up the height and width of the QR code(default is 100)
3. level = (‘L’, ‘M’, ‘Q’, ‘H’).
4.bacground = The default value is white.
5. backgroundAlpha =Sets up the opacity of the foreground
6.mime = used for setting up the mime type for the output image.
7.padding=  sets up the padding in QR Code,
8. canvas =The value type is boolean and used for outputting a canvas element if sets to true. However, the default value is set to false.

