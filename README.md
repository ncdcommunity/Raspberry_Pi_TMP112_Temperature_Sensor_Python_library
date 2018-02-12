[![ TMP112](TMP112_I2C.png)](https://store.ncd.io/product/tmp112-temperature-sensor-%C2%B1-5c-12-bit-i2c-mini-module/).

#  TMP112

The TMP112 offers high-accuracy digital temperature measurement in a low-cost package.The TMP112 is ideal for NTC/PTC thermistor replacement where high accuracy is required. 
This Device is available from www.ncd.io 

[SKU: TMP112]

(https://store.ncd.io/product/tmp112-temperature-sensor-%C2%B1-5c-12-bit-i2c-mini-module/)
This Sample code can be used with Raspberry Pi.

Hardware needed to interface TMP112 temperature sensor With Raspberry Pi :
1. <a href="https://store.ncd.io/product/tmp112-temperature-sensor-%C2%B1-5c-12-bit-i2c-mini-module/">TMP112 temperature sensor</a>
2.  <a href="https://store.ncd.io/product/i2c-shield-for-raspberry-pi-3-pi2-with-outward-facing-i2c-port-terminates-over-hdmi-port/">Raspberry Pi I2C Shield</a>
3. <a href="https://store.ncd.io/product/i%C2%B2c-cable/">I2C Cable</a>

## Python
Download and install smbus library on Raspberry pi. Steps to install smbus are provided at:

https://pypi.python.org/pypi/smbus-cffi/0.5.1

Download (or git pull) the code in pi. Run the program.

```cpp
$> python TMP112.py
```
The lib is a sample library, you will need to calibrate the sensor according to your application requirement.
