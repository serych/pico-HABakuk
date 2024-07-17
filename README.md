# Picoballoon tracker board based on RP2040
In this project I am developing a lightweight small balloon tracker board based on the RP2040 processor. 
The primary software intended for this board is [pico-WSPRer](https://github.com/EngineerGuy314/pico-WSPRer). 
## Basic parameters
- Board contains: 
    - RP2040 processor (with memory and crystal and RGB LED for status indication), 
    - position for soldering GPS module type ATGM336H (or pin compatible), 
    - SPV1040T MPPT inverter for solar cells 
- Flight interfaces: 
    - antenna, 
    - solar panels, 
    - ultracapacitor (optional), 
    - GPS antenna
    - additional GPIO pins GPIO10-GPIO13 + ADC0
- The pre-flight electronics parts are located on the breakaway part of the board, which is also equipped with test pins so that the flight part can be connected even after breakaway. 
- Pre-flight interfaces: 
    - USB connector and stabilizer for powering the board via USB, 
    - debug interface of RP2040, 
    - RESET and USB_BOOT buttons
## Images
![3D model - top side](https://github.com/serych/pico-HABakuk/blob/master/img/board3D-top.jpg?raw=true)
![3D model - bottom side](https://github.com/serych/pico-HABakuk/blob/master/img/board3D-bot.jpg?raw=true)
![board dimensions](https://github.com/serych/pico-HABakuk/blob/master/img/board-dim.JPG?raw=true)

### This project is licensed under the terms of the CERN Open Hardware Licence Version 2 - Weakly Reciprocal.

