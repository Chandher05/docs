

“Dyu - Efficient and fast handling of restaurant bills using Image recognition and real time cloud storage”

## Features!

  - Make a group with friends
  - Upload an image of the bill
  - Create a digital  copy of the bill
  - Select items you ate
  - You have an individual summary of what you ate and tax calculated only for you
  - Pay using our wallet (Tied with payment gateway is in the works)


Dyu, is an app that takes an image which is converted to digital copy of the bill. 


### Tech

Dyu uses a number of open source projects to work properly:

* Firebase - Cloud Database
* jQuery - Javascript Framework
* Apache2 - Server to host the image processing model
* Cordova - To create a Hybrid app


### Installation


Install the dependencies and start the server.



##### Setting up the Image Processing Server:

- Install a local server software like XAMP or Apache web server.
- Launch the server and set your local IP as 192.168.43.76
- Place the python script for image processing, ocr.py and the server side script called server.php in a folder called Test2 in the www folder of your server.
- Install Tesseract OCR on your system and download the english language files.
- Have Python 3.x installed on your system in the path C:/Python36.
- Install the opencv library, Pytesseract library and Pillow library for Python using pip.
- Change the value of tesseract_cmd with the path at which you have installed Tesseract on your system in the pytesseract.py file in your Python library fold

#### Setting up Firebase 
- Open up firebase console
- Create an API key
- Set this API key in the JS code

#### Creating the App using Apache Cordova
- Installing the Cordova CLI
```sh
 $ sudo npm install -g cordova
```
- Create the App
```sh
$ cordova create dyu com.app.dyu Project_Dyu
```
- Add platforms
```sh
$ cordova platform add ios
$ cordova platform add android
````


#### Apk generated
- Once you have the APK generated from the Apache Cordova
- Install .apk file onto your phone

Free to use dyu










