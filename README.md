# ESP OS
## The first ever Operating system for your ESP device

ESP OS is first(but not least) Operating system for ESP8266 NodeMCu v2.

To unleash the full capabilities of this operating system, connect the [Oled display](https://abc-rc.pl/pl/products/wyswietlacz-oled-0-96-128x64-na-i2c-ssd1306-bialy-12052.html) to your ESP device.

Download ESP OS from [here](https://github.com/KrajaniXPolska1/ESP_OS/releases).

## Features

- working startup image
- some commands
- working internet connection
- 
# Commands
- blink command: blink a built in led
- about command: show simple info about **ESP OS**
- author command: show simple info about author os **ESP OS**
- logo command: show logo of **ESP OS**
- random number command: generates random number in the range from 1 to 99
- time commnad: show actual time
- ip command: show your ip in serial monitor 

# Installation
to install **ESP OS** on the your ESP device you need to add esp boards to arduino ide.

- load the .ino file to arduino ide
- add your network name and your network password
- set your time zone(type your time zone in seconds)
- upload ESP OS to your esp board

# Changelog 

## 0.2
- added internet connection
- added real time clock
- recreated ESP OS logo

## 0.1
- added about command
- added author command
- added blink command
- added random number command
- added logo command
