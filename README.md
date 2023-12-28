# ESP OS
## The first ever Operating system for your ESP device

ESP OS is first(but not least) Operating system for ESP8266 NodeMCu v2.

To unleash the full capabilities of this operating system, connect the [Oled display](https://abc-rc.pl/pl/products/wyswietlacz-oled-0-96-128x64-na-i2c-ssd1306-bialy-12052.html) to your ESP device.

Download ESP OS from [here](https://github.com/KrajaniXPolska1/ESP_OS/releases).

## Features

- working startup proccess
- some commands
- working internet connection

  
# Commands
- _blink_ command: blink a built in led
- _about_ command: show simple info about **ESP OS**
- _author_ command: show simple info about author os **ESP OS**
- _logo_ command: show logo of **ESP OS**
- _random number_ command: generates random number in the range from 1 to 99
- _time_ commnand: show actual time
- _ip_ command: show your ip in serial monitor
- _weather_ command: shows actual weather
- _clear_ command: clear your display

# Installation
to install **ESP OS** on the your ESP device you need to add esp boards to arduino ide.

- load the .ino file to arduino ide
- add your network name and your network password
- set your time zone(type your time zone in seconds)
- set your city name and these country letters
- upload ESP OS to your esp board

# Changelog 

## 0.3
- added _weather_ command
- changed look of _time_ and _random number_ commands
- added startup process
- added _clear_ command

## 0.2.1
- changed position of lower bar in the ESP OS logo what shows in the _about_ and _author_ commands

## 0.2
- added internet connection
- added real time clock
- recreated ESP OS logo
- added _time_ command
- added _ip_ command

## 0.1
- added _about_ command
- added _author_ command
- added _blink_ command
- added _random number_ command
- added _logo_ command
