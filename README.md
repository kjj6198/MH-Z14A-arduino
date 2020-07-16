# CO2 Sensor (MH-Z14A)

An example for using MH-Z14A and Arduino Uno to detect CO2 level.
It'll receive the result from MH-Z14A via pin 3,4 by UART communication and send the result via Hardware Serial (tx, rx) which is 0 and 1 in Arduino Uno.

## MH-Z14A

- [Datasheet](./mh-z14a.pdf)

MH-Z14A is a `NDIR` sensor.

* Make sure power supply range is stable and fit, or sensor might output very low number (e.g: 410ppm) 
* At beginning (around 30 seconds), the sensor response is not correct.
