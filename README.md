# CHMKchallo
## _The Ultimate Patient Monitoring System_

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

CHMKchallo is the cloud enabled patient side MCU based sensor array that tracks all the stats using all its sensors
and sends it over to firebase cloud as well as hosts it locally

- Attach sensors
- Enter Newtwork and Firebase credentials
- ✨Magic ✨

## Front-End

[Phuljhari](https://github.com/1719pankaj/Phuljhari) is an accompanying android applicaition for this project.

## Installation

CHMKchallo requires a few dependencies to run.

Install the dependencies and start the server.

```sh
Firebase Arduino Client Library for ESP8266 and ESP32 -Mobitz
DHT Sensor Library - Adafruit
OneWire - Paul Stoffregen
DallasTemperature - Miles Burton
MAX30100lib - OXullo Interscans
```

Setup Firebase

```sh
Create a firebase project
Disable all analytics
Enable anonymous sign-ins
Create a RealTime Database (in test mode)
Copy the DB url
Goto Project Settings >> General >> Web API Key
Copy the Key
```


## License

MIT

**Free Software, Hell Yeah!**
