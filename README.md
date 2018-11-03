# Arcade controller

Custom arcade game style controller with USB interface

## Concept

TODO: Fill in this section .....

![Block diagram](./Block%20diagram.png)

## I²C addresses

| I²C address | Device                                  |
| ----------- | --------------------------------------- |
|    0x38     | PCF8574 GPIO expander driving the LCD   |
|    0x39     | PCF8574 GPIO expander on button board 1 |
|    0x3A     | PCF8574 GPIO expander on button board 2 |
|    0x3B     | PCF8574 GPIO expander on button board 3 |
|    0x3C     | PCF8574 GPIO expander on button board 4 |
|    0x3D     | PCF8574 GPIO expander on button board 5 |
|    0x3E     | PCF8574 GPIO expander on button board 6 |
|    0x3F     | PCF8574 GPIO expander on button board 7 |

*All I²C addresses are specified in 7-bit format (i.e. the read/write bit is not considered part of the address).*
