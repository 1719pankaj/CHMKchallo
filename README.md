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

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

