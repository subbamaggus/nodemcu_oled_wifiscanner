# nodemcu_oled_wifiscanner

## simple example

## setup
hardware used:
- NodeMCU V3
- Adafruit OLED Display 128x64 px
- Breadboards

## function

the nodemcu makes use of wifi and i2c/display driver

it will scan for wifi networks and prints out information via serial connection and on display

hint: i read, that the order is based on signal strength. but that does not seem to be true

## wiring

https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/
Section: ESP8266 12-E NodeMCU Kit

### Display <> NodeMCU
| Display | Pin Label | Pin Description |
|---------|-----------|-----------------|
| VCC     | 3V        | 3.3V            |
| GND     | G         | GND             |
| SCL     | D1        | GPIO5           |
| SDA     | D2        | GPIO4           |

## thanks to

http://en.radzio.dxp.pl/bitmap_converter/


## picture of the running setup

![Breadboard](https://github.com/subbamaggus/nodemcu_oled_wifiscanner/blob/main/live_image.jpeg?raw=true)
