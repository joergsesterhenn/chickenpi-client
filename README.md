<img style="float: right;" alt="chickenpi logo" src="https://github.com/joergsesterhenn/chickenpi/raw/master/chickenpi.png" height="200">

# chickenpi-client  [![Build Status](https://travis-ci.org/joergsesterhenn/chickenpi-client.svg?branch=master)](https://travis-ci.org/joergsesterhenn/chickenpi-client) <a href="https://sonarcloud.io/dashboard?id=de.chickenpi:chickenpi-client"><img alt="quality gate status" src="https://sonarcloud.io/api/badges/gate?key=de.chickenpi:chickenpi-client"/></a> <a href="https://david-dm.org/joergsesterhenn/chickenpi-client"> <img title="dependencies status" src="https://david-dm.org/joergsesterhenn/chickenpi-client/status.svg"/></a><a href="https://david-dm.org/joergsesterhenn/chickenpi-client?type=dev" title="devDependencies status"><img src="https://david-dm.org/joergsesterhenn/chickenpi-client/dev-status.svg"/></a>
Chickenpi is a node.js/raspberry pi chicken coop management solution - currently in inception phase.
This repository holds the client. 

## Components 
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

# Architecture of chickenpi
* [chickenpi overview](https://github.com/joergsesterhenn/chickenpi)
* [chickenpi-app](https://github.com/joergsesterhenn/chickenpi-app)

<img alt="architecture" src="https://github.com/joergsesterhenn/chickenpi/blob/master/chickenpi_architecture.png" height="400">
