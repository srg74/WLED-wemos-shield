# WLED wemos shield with [plug-in add-ons](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Add-ons)

[![release](https://img.shields.io/github/v/release/srg74/WLED-wemos-shield)](https://img.shields.io/github/v/release/srg74/WLED-wemos-shield)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/srg74/WLED-wemos-shield/blob/master/LICENSE)
[![custom firmware](https://img.shields.io/static/v1?label=Custom&message=firmware&color=blue&style=flat-square)](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware)
[![Official releases](https://img.shields.io/static/v1?label=WLED&message=firmware&color=green&style=flat-square)](https://github.com/Aircoookie/WLED/releases)
[![WLED app](https://img.shields.io/static/v1?label=WLED&message=app&color=green&style=flat-square)](https://github.com/Aircoookie/WLED-App)
[![Desktop app](https://img.shields.io/static/v1?label=WLED&message=Desktop-app&color=violet&style=flat-square)](https://github.com/WoodyLetsCode/WLED-GUI/releases/)

I appreciate your support for my project! [![donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/donate/?hosted_button_id=VU7L89Z2RR7S4)

## Wi-Fi LED shield based on Wemos D1 Mini original or clones, Wemos ESP32 D1 mini for WLED firmware

- Detailed assembly and options information is [here](https://github.com/srg74/WLED-wemos-shield/wiki)

[![Shield](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/Images/Board%20with%20OLED.jpg)](https://github.com/srg74/WLED-wemos-shield/wiki)

### For changes in design please see [changelog.md](https://github.com/srg74/WLED-wemos-shield/blob/master/Changelog.md)

## PCB ordering

- [Ordering](https://www.pcbway.com/project/shareproject/WLED_wemos_shield.html) - $5 for 10 PCBs very good quality.
- [Sign in and save](https://www.pcbway.com/setinvite.aspx?inviteid=83580) - Helping me to save some money for development.
- [Ready to use fully assembled shield on Tindie](https://www.tindie.com/stores/serg74)

## Wi-Fi LED controller with following features

- Very easy to configure for your project;
- Easy to solder components;
- Level shifter for relaible data signal;
- Solder jumpers for flexible confiuration;
- Power selector (e.g 5VDC or 12/24VDC);
- Can be configured for 1 (data) wire and 2 (data, clock) wires addressable LED strips;
- Analog and Digital input for sound reactive compatability;
- Button option on board;
- Relay for power saving feature (without disconnecting power from LED strip it still consuming current even if none of LEDs is lit);
- Auxilary power for additional relay or other 5VDC powered devices;
- I2C connector for OLED display or other devices that might be integrated in a feature;
- I2S connectivity for ESP32 boards;
- Optional IR reciever;
- Optional Dallas temperature sensor;
- Optional I2C sensors;
- 4 or 3 pin PWM fan circuit.

## Firmware used

- [WLED shield specific repository](https://github.com/srg74/WLED/tree/WLED_wemos_shield) - WLED repository fork with changes to use with shield
- [WLED repository](https://github.com/Aircoookie/WLED) - Aircoookie original WLED repository
- [WLED repository](https://github.com/atuline/WLED) - Sound reactive WLED fork repository
- [Custom firmware builds](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware) - Custom bin files for various configurations
