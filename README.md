# oled-pixel-mapper
Designed to export LCD/OLED pixel data to uint8_t format. Can be used to control displays through Arduino/TI/RPi/PIC

Live version can be found here
http://preee.github.io/oled-pixel-mapper/

![alt tag](http://preee.github.io/oled-pixel-mapper/sample.jpg)
![alt tag](http://preee.github.io/oled-pixel-mapper/screenshot.png)

## How to use
```
const uint8_t test_bitmap[] PROGMEM = {
    0x0, 0xff, 0xff, 0x18, 0x18, 0x18, 0x18, 0x18,
};
```
