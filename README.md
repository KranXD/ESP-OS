# ESP OS ![Logo](https://github.com/KranXD/ESP-OS/blob/main/logo.png)
## The first ever Operating system for your ESP device

ESP OS is first(but not least) Operating system for ESP8266 NodeMCu v2.

To unleash the full capabilities of this operating system, connect the [Oled display](https://abc-rc.pl/pl/products/wyswietlacz-oled-0-96-128x64-na-i2c-ssd1306-bialy-12052.html) to your ESP device.

## Features

- Working startup proccess
- Some commands
- Working internet connection
//- Working desktop environment. Download it from [here](https://github.com/KrajaniXPolska1/Espie).

  
# Commands
- _blink_ command: blink a built in led
- _about_ command: show simple info about **ESP OS**
- _author_ command: show simple info about author os **ESP OS**
- _logo_ command: show logo of **ESP OS**
- _random number_ command: generates random number in the range from 1 to 99
- _ip_ command: show your ip in serial monitor
- _weather_ command: shows actual weather
- _clear_ command: clear your display
- _loading screen_ command: show loading screen from startup

# Installation
To install **ESP OS** on the your ESP device you need to add esp boards to arduino ide.

- Load the .ino file to arduino ide
- Add your network name and your network password
- Set your time zone(type your time zone in seconds)
- Set your city name and these country letters
- Upload ESP OS to your esp board

# Warning
ESP OS can randomly restart in due to reloading Espie which was described on the Espie github

# Changelog 

## 0.4
- Added it from here
- Removed _time_ command
- Recreated logo (again)
- added element to startup screen
- added _loading screen_ command

## 0.3
- Added _weather_ command
- Changed look of _time_ and _random number_ commands
- Added startup process
- Added _clear_ command

## 0.2.1
- Changed position of lower bar in the ESP OS logo what shows in the _about_ and _author_ commands

## 0.2
- Added internet connection
- Added real time clock
- Recreated ESP OS logo
- Added _time_ command
- Added _ip_ command

## 0.1
- Added _about_ command
- Added _author_ command
- Added _blink_ command
- Added _random number_ command
- Added _logo_ command
