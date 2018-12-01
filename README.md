# Modular controller

.....

## Concept

TODO: Fill in this section .....

![Block diagram](./Block%20diagram.png)

## System components

* PCBAs
  * [Main board](https://github.com/PhilboBaggins/arcade-controller-pcb-main-board)
  * [Button board](https://github.com/PhilboBaggins/arcade-controller-pcb-button-board)
  * [User interface board](https://github.com/PhilboBaggins/arcade-controller-pcb-user-interface)
* [Firmware](https://github.com/PhilboBaggins/arcade-controller-firmware)

## Projects using these components

### Mine

* [Arcade controller](https://github.com/PhilboBaggins/arcade-controller)

### Other peoples

None yet :(

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
|    ????     | ??????? EEPROM                          |

*All I²C addresses are specified in 7-bit format (i.e. the read/write bit is not considered part of the address).*
