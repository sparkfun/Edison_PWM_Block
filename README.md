SparkFun Edison PWM Block
==================================================

![SparkFun Edison PWM Block](https://cdn.sparkfun.com//assets/parts/1/0/0/4/4/13042-01.jpg)

[*SparkFun Edison PWM Block(DEV-13042)*](https://www.sparkfun.com/products/13042)


This card adds eight channels of PWM control to the Edison's I<sup>2</sup>C bus. While the PWM output can be used for any generic PWM application, it is specifically intended to provide drive control for up to eight standard hobby-type servo motors. To that end, it has an independent input for supply voltage for the servos above the normal range of the Edison, and 8 connections that support the most common pinout of hobby servo motors.

The PCA9685 provides open-collector or push-pull output capabilities; as the intended target is servo motors, the board has a pull-up resistor to the independently connected servo supply voltage. The PCA9685 has an independent clock that can be operated at 50Hz, for servo control; at that frequency, the 12-bit resolution of the device provides approximately 200 steps of resolution for a servo motor.

The PCA9685 can be used as an open collector current driver for LEDs up to 25mA as well. Six solder jumpers allow the user to attach up to 63 of these cards to a single Edison, or to adjust the address of the PCA9685 to avoid collision with other addresses on the bus.

Repository Contents
-------------------
* **/Hardware** - All Eagle design files (.brd, .sch)
* **/Production** - Test bed files and production panel files

License Information
-------------------
The hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).
The code is beerware; if you see me (or any other SparkFun employee) at the local, and you've found our code helpful, please buy us a round!

Distributed as-is; no warranty is given.
