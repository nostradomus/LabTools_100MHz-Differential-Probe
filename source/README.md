## Firmware

This folder contains the firmware source code related to the project :

version | name             | description
--------|------------------|--------------------------------------------------------------------------------------------
v1.0    | central_cube.ino | cleaned-up and commented version, with improved display animation, and sound
v1.0    | feynman_cube.ino | cleaned-up and commented version, with improved digits, two different animations, and sound
v1.0    | pinball_cube.ino | cleaned-up and commented version, with improved digits, two different animations, and sound

The above Arduino sketches are to be loaded in the ATmega328p chip of the respective µ-controller board.

### External libraries
Some of these sketches require external libraries. Please check below table for cross-references. This source folder also contains snapshots from these libraries at the time of build (tested version). Libraries can be installed using the [standard procedure](https://www.arduino.cc/en/Guide/Libraries).

library              | to be used in    | origin                                               | docs                                                             | notes
---------------------|------------------|------------------------------------------------------|------------------------------------------------------------------|---------------------------------------------
lib-tm1638           | central_cube.ino | [link](https://github.com/rjbatista/tm1638-library/) | [link](https://github.com/rjbatista/tm1638-library/wiki)         | to be used for the 16-digit display
lib-ledcontrol       | pinball_cube.ino | [link](https://github.com/wayoda/LedControl/)        | [link](http://wayoda.github.io/LedControl/)                      | to be used for the 8x8 LED display module
lib-adafruitneopixel | feynman_cube.ino | [link](https://github.com/adafruit/Adafruit_NeoPixel/) | [link](https://learn.adafruit.com/adafruit-neopixel-uberguide) | to be used for the feynman wiggly line
lib-ledcontrol       | feynman_cube.ino | [link](https://github.com/wayoda/LedControl/)        | [link](http://wayoda.github.io/LedControl/)                      | to be used for the 8x8 LED display module
