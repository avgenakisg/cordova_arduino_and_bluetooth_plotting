# Bluetooth plotting with Cordova and Arduino

[![Build Status](https://img.shields.io/github/stars/avgenakisg/cordova_arduino_and_bluetooth_plotting.svg)](https://github.com/avgenakisg/cordova_arduino_and_bluetooth_plotting)
[![Build Status](https://img.shields.io/github/forks/avgenakisg/cordova_arduino_and_bluetooth_plotting.svg)](https://github.com/avgenakisg/cordova_arduino_and_bluetooth_plotting)
![Bintray](https://img.shields.io/badge/version-1-yellowgreen.svg)

[![forthebadge](http://forthebadge.com/images/badges/built-with-love.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/uses-js.svg)](http://forthebadge.com)
[![forthebadge](http://forthebadge.com/images/badges/uses-html.svg)](http://forthebadge.com)


Cordova simple app for plotting values using an HC-05 bluetooth ,  arduino uno and epoch js library. <br>
Based on examples : https://github.com/don/BluetoothSerial <br>

This project created in order to plot values coming from a cardiograph (ECG) to mobile phone using 
a bluetooth HC-05 module and arduino.

I created a very simple design. <br>
In the first box we can read the data comming from serial port <br> 
In the second box I plot the values comming from bluetooth using epoch js real time plotting <br>
In the third box I count Pulses/second using a simple algorithm (count the time and the number of spikes 
using a max value limit) <br>

![alt tag](screen.png)

Steps for creation:

1.Use arduino and HC-05 to send values from arduino to mobile phone using bluetooth<br>
2.Download cordova and build the project <br>
3.Open bluetooth on mobile device and connect the HC-05 <br>
4.Click on connect to get real time data from HC-05 to mobile 


Usefull links:<br>
1.http://epochjs.github.io/epoch/  <br>
2.http://www.ebay.com/bhp/hc-05  <br>
3.https://cordova.apache.org/

