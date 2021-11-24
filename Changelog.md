# Sound reactive board is depricated. All features will be available on Universal WLED Wemos shield as plug-in add-on

## v3.0

- All configuration solder jumpers moved to bottom off the shield for easy access
- Added alternate relay model SRA-05VDC-SL-C 15A nominal

## v2.1

- Added possibility to switch digital out 2 -> clock pin (GPIO1/GPIO3)
- Added header for Auxiliary 5V (required buck converter upgrade to 1000mA)
- Wiki updated for shields v2.0 and above
- Shield mounting holes now is 3mm

## v2.0

- Added copability to connect up to 4 LED strips with level shifting.
- Added more flexibility with solder on jumpers.

### Added [terminals add-on](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Add-ons)

### Added [linear audio input plug-in, and digital ICS-43434 microphone add-on boards](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Add-ons) for Shield v1.5 and up

### v1.51

- Minor update. Fixed library and gerber files errors.
- Added [WLED firmware v0.11 Build 2012070](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.11)
- Old builds removed.
- Added board STEP file.

### v1.5

- Exposed additional pins for I2S microphones. :bangbang: ESP32 boards only :bangbang:
- Removed header 3 positions labeled AUDIO.
- Added header 6 poitions labeled SOUND.
- Added second row of headers for ESP32 boards connectivities.
- [Firmware v0.11_beta](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.11_beta_2011154) available for testing

### v1.3

- Removed resistor R1 connected to GPIO14. Instead of header placed IR receiver.
- Added on board momentary push button connected to GPIO0. Removed header.
- Added [WLED firmware v0.10.2 build_2010290](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.10.2_2010290)

### v1.2

- Added more space to acomodate different size of ESP32 mini boards. Apperently some boards is slightly bigger then proto board.
- Added Wiki link to [3D printed enclosure](https://www.thingiverse.com/thing:4313485) by @rboers
