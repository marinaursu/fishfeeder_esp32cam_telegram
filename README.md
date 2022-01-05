# Fish feeder
![My Badge](/src/docs/badge_ff.svg)

>Fish feeder based on ESP32CAM dev kit and controlled through telegram bot

### Authors: 
[IBishopI](https://github.com/IBishopI) and [Marina Ursu](https://github.com/marinaursu)

## Description:

This project is aimed at people who love:smiling_face_with_three_hearts: aquarium fish:tropical_fish: but spend too much time at work or on business trips.
An autonomous feeder makes it possible to feed your pets from anywhere in the world.

## Capabilities:
- [x]  Set the feeding portion
- [x]  Schedule feeding once a day
- [x]  Take a picture (with and without flash)
- [x]  Find out the status and time of the last feeding
- [ ]  (further release) Clearing the blockage
- [ ]  (further release) Light and thermostat control
- [ ]  (further release) Measurement of water temperature
- [ ]  (further release) Battary cell life-time and life-keeping functions

### Software requirements:
- Arduino IDE 1.8 and higher [here](https://www.arduino.cc/en/software)
- ESP32 core 1.0.6 (most stable for my opinion) [github](https://github.com/espressif/arduino-esp32) or [json](https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json)
- [Universal Telegram Bot library](https://github.com/witnessmenow/Universal-Arduino-Telegram-Bot)
- CH340 driver if you will use USBASP programmer with ch340 chip - [Windows](https://sparks.gogo.co.nz/assets/_site_/downloads/CH34x_Install_Windows_v3_4.zip), [Mac](https://github.com/adrianmihalko/ch340g-ch34g-ch34x-mac-os-x-driver/raw/master/CH34x_Install_V1.5.pkg), [Linux](https://sparks.gogo.co.nz/assets/_site_/downloads/CH340_LINUX.zip "Already built in kernel but if isnt you can download it by click this link") or you can findout it on [official website](http://www.wch.cn/download/ch341ser_zip.html)
- Telegram app on your phone:iphone: or laptop:computer:

### Hardware requirements:
- USB ASP progremmer

![](/src/docs/usb_asp_programmer.png)
- ESP32cam

![](/src/docs/esp_32_cam.png)
- Servo

![](/src/docs/6CH_RC_SG90.png)
- DC-DC stepup converter 3.7 to 5v

![](/src/docs/stepup.png)
- Battary charger TP4056

![](/src/docs/tp4056_type_C.png)
- :battery:Li-ion battary cell (18650)

## How to setup telegram bot
