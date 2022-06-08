# Beer Analytics

### Introduction

### Installation
  * Keg Management and pour tracking is is handled by [Kegbot Server](https://kegbot.org).  This data can be accessed by Kegbot's REST API.  Real-time pour data can also be sent via Webhook.  There are a variety of implementations for Kegbot; in this project it is running on a Raspberry Pi.
  * Flow Sensors:  Using Swissflow SF-800.  There are cheaper options available on Adafruit, Amazon, etc.  Considerations may include calibration accuracy and whether the components are "food grade."
  * Arduino Nano:  Sketch available here:  [http://github.com/Kegbot/kegboard](http://github.com/Kegbot/kegboard).
  * Temperature Sensor(s):  DS18B20 Temperature Probe was used. If you are using a temperature sensor, you will have to connect a 4.7k resistor between the 5V line and the signal line of the sensor.  There are a variety of ways to implement this (i.e., with Arduino as described [here](https://create.arduino.cc/projecthub/TheGadgetBoy/ds18b20-digital-temperature-sensor-and-arduino-9cc806), or with a Pi, as described [here](https://learn.adafruit.com/adafruits-raspberry-pi-lesson-11-ds18b20-temperature-sensing).  In this project temperature data is sent to Splunk Edge Hub via MQTT.
  * Weight:  
### Acknowledgments & References
  * [https://kegbot.org](https://kegbot.org)
  * Kegbot Github Repo:  [https://github.com/Kegbot/kegbot-server/](https://github.com/Kegbot/kegbot-server/)
  * Kegbot Discussion Forum [https://forum.kegbot.org/](https://forum.kegbot.org/).  New Installation & Hardware Discussion [Thread](https://forum.kegbot.org/t/kegberry-kegbot-new-installation/1017/4).
  * Kegbot Documentation:  [https://kegbot-server.readthedocs.io/en/latest/](https://kegbot-server.readthedocs.io/en/latest/)
