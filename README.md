# Beer Analytics

### Introduction

### Installation
  * Keg Management and pour tracking is is handled by [Kegbot Server](https://kegbot.org).  This data can be accessed by Kegbot's REST API.  Real-time pour data can also be sent via Webhook.  There are a variety of implementations for Kegbot; in this project it is running on a Raspberry Pi.
  * Flow Sensors:  Using Swissflow SF-800.  There are cheaper options available on Adafruit, Amazon, etc.  Considerations may include calibration accuracy and whether the components are "food grade."
  * Arduino Nano:  Sketch available here:  [http://github.com/Kegbot/kegboard](http://github.com/Kegbot/kegboard).
  * Temperature:  DS18B20 Temperature Sensor. If you are using a temperature sensor, you will have to connect a 4.7k resistor between the 5V line and the signal line of the sensor.
  * Weight:  
### Acknowledgments & References
  * [https://kegbot.org](https://kegbot.org)
  * Kegbot Github Repo:  [https://github.com/Kegbot/kegbot-server/](https://github.com/Kegbot/kegbot-server/)
  * Kegbot Discussion Forum [https://forum.kegbot.org/](https://forum.kegbot.org/).  New Installation & Hardware Discussion [Thread](https://forum.kegbot.org/t/kegberry-kegbot-new-installation/1017/4).
  * Kegbot Documentation:  [https://kegbot-server.readthedocs.io/en/latest/](https://kegbot-server.readthedocs.io/en/latest/)
