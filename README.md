<img style="float: right;" alt="chickenpi logo" src="https://github.com/joergsesterhenn/chickenpi/raw/master/chickenpi.png" height="200">

# chickenpi-client
Chickenpi is a node.js/raspberry pi chicken coop management solution - currently in inception phase.
This repository holds the client. 

# Architecture
<img alt="architecture" src="https://github.com/joergsesterhenn/chickenpi/blob/docs/chickenpi.png" height="400">

## Software 
### [cickenpi-client](https://github.com/joergsesterhenn/chickenpi-client) [![Build Status](https://travis-ci.org/joergsesterhenn/chickenpi-app.svg?branch=docs)](https://travis-ci.org/joergsesterhenn/chickenpi-app) <a href="https://sonarcloud.io/dashboard?id=de.chickenpi:chickenpi-app"><img alt="quality gate status" src="https://sonarcloud.io/api/badges/gate?key=de.chickenpi:chickenpi-app"/></a> <a href="https://david-dm.org/joergsesterhenn/chickenpi-app"> <img alt="dependencies up to date status" src="https://david-dm.org/joergsesterhenn/chickenpi-app.svg"/></a>
* [agenda](https://github.com/agenda/agenda) 
* [onoff](https://github.com/fivdi/onoff) 
* [socket.io](https://github.com/socketio/socket.io)
* [firebase-sdk](https://firebase.google.com/support/release-notes/js)


## Hardware
* raspberry pi 2 + edimax USB Wifi dongle
* temperature and humidity sensor DHT22
* motor controller board L98N + servo motor (for coop door)
* 4 relay module (for lights, ...)

_Ideas for later_
* [RFID](http://www.sunspot.co.uk/Projects/RFID/Chickens_RFID.html)

