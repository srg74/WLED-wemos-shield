# WLED wemos shield with <a href=https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Add-ons>plug-in add-ons</a>.
 
[![](https://img.shields.io/github/v/release/srg74/WLED-wemos-shield)](https://img.shields.io/github/v/release/srg74/WLED-wemos-shield)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square)](https://github.com/srg74/WLED-wemos-shield/blob/master/LICENSE)
[![](https://img.shields.io/static/v1?label=Custom&message=firmware&color=blue&style=flat-square)](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware)
<a href="https://travis-ci.com/srg74/WLED.svg?branch=WLED_wemos_shield"><img src="https://img.shields.io/travis/com/srg74/WLED?style=flat-square"></a>
[![](https://img.shields.io/static/v1?label=WLED&message=firmware&color=green&style=flat-square)](https://github.com/Aircoookie/WLED/releases)
[![](https://img.shields.io/static/v1?label=WLED&message=app&color=green&style=flat-square)](https://github.com/Aircoookie/WLED-App)
[![](https://img.shields.io/static/v1?label=WLED&message=Desktop-app&color=violet&style=flat-square)](https://github.com/WoodyLetsCode/WLED-GUI/releases/)

I appreciate your support for my project! [![](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=VU7L89Z2RR7S4&source=url)

## Wi-Fi LED controller based on Wemos D1 Mini original or clones, Wemos ESP32 D1 mini for WLED firmware.
-   Detailed assembly and options <a href=https://github.com/srg74/WLED-wemos-shield/wiki>information is here </a>
<img src="https://github.com/srg74/WLED-wemos-shield/blob/master/resources/Enclosure/Board%20with%20OLED.jpg" width="40%">


### For changes in design please see <a href=https://github.com/srg74/WLED-wemos-shield/blob/master/Changelog.md>changelog.md</a>

## PCB ordering

-   [Ordering](https://www.pcbway.com/project/shareproject/WLED_wemos_shield.html) - $5 for 10 PCBs very good quality.
-   [Sign in and save](https://www.pcbway.com/setinvite.aspx?inviteid=83580) - Helping me to save some money for development.
-   [Ready to use fully assembled shield on Tindie](https://www.tindie.com/stores/serg74)

```
Wi-Fi LED controller with following features
```
-   Very easy to configure for your needs;
-   Easy to solder components;
-   Level shifter for relaible signal;
-   Solder jumpers for flexible confiuration;
-   Power selector (e.g 5VDC or 12/24VDC);
-   Can be configured for 1 wire and 2 wire addressable LED strips;
-   Analog and Digital input for sound reactive compatability;
-   Button option on board (depend on type of addressable LED strip);
-   Relay for power saving feature (without disconnecting power from LED strip it still consuming mA per LED even if none of LEDs is lit);
-   Auxilary power for additional relay or other 5VDC powered devices; 
-   I2C connector for OLED display or other devices that might be integrated in a feature;
-   I2S connectivity for ESP32 boards;
-   Optional IR reciever;
-   Optional Dallas temperature sensor;
-   Optional I2C sensors.

## Firmware used

-   [WLED shield specific repository](https://github.com/srg74/WLED/tree/WLED_wemos_shield) - WLED repository fork with changes to use with shield
-   [WLED repository](https://github.com/Aircoookie/WLED) - Aircoookie original WLED repository
-   [WLED repository](https://github.com/atuline/WLED) - Sound reactive WLED fork repository
-   [Custom firmware builds](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware) - Custom bin files for various configurations
#### Board creation is inspired by https://github.com/Aircoookie/WLED/wiki
