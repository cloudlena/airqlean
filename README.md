# AirQlean

An air quality monitor based on [ESPHome](https://esphome.io/)

## Hardware

- Microcontroller: [WeMos D1 Mini](https://www.wemos.cc/en/latest/d1/d1_mini.html)
- Sensors: [ENS160 and BME280](https://wiki.dfrobot.com/Multi_function_Environmental_Module_ENS160_BME280_SKU_SEN0335)
- LEDs: [Red, Yellow, Green](https://www.bastelgarage.ch/7mm-led-mini-traffic-light)
- Optional Display: [16x2 LCD with I2C Module](https://www.bastelgarage.ch/lcd1602-lcd-blue-display-with-i2c-module)

## Software

Defined using ESPHome. See [airclean.yaml](./airqlean.yaml).

### Flashing

1. Plug the microcontroller into your computer
1. Run `esphome run airqlean.yaml`
