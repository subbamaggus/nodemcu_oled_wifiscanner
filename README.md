# nodemcu_oled_wifiscanner

## simple example

this simple example demonstrates how to use
- NodeMCU V3
- Adafruit OLED Display 128x32 px

## function

the nodemcu makes use of wifi and i2c/display driver

it will scan for wifi networks and prints out information via serial connection and on display

hint: i read, that the order is based on signal strength. but that does not seem to be true

## wiring

| Display | Pin Label | Pin Description  |
|---------|-----------|------------------|
| VCC     | 3V        | 3.3V             |
| GND     | G         | GND              |
| SCL     | D1        | GPIO5            |
| SDA     | D2        | GPIO4            |


https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/

Section: ESP8266 12-E NodeMCU Kit


## thanks to

http://en.radzio.dxp.pl/bitmap_converter/


## picture of the running setup

![Breadboard](https://github.com/subbamaggus/nodemcu_oled_wifiscanner/blob/main/live_image.jpeg?raw=true)
