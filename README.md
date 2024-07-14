# DevKeyboard
PC Keyboard with embedded functionality for fast prototyping and testing external devices.


## Main purpose of DevKeyboard
The idea of ​​the project is to improve the hardware developing process by testing external devices that can be connected and communicated by i2c, spi, one wire protocols.
No additional external systems such as Arduino are needed, just keebord that you can control with commands via appliaction on your computer.
![Alt text](DevBoard_Case.png?raw=true "Keyboard case prototype.")

Prototype board version 1.0 consist of:
- STM32G431RBT6 chip,
- USB-C connector,
- Hotswap Kailh sockets for MX Cherry switches,
- Onboard 3.3V two LDO stabilizers for STM32 chip and external power connector + 5V BUS,
- 8x2 pin spring loaded Phoenix Contact connectors for fast and easy connectivity,
- Incremental encoder.

