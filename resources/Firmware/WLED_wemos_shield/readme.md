# Firmware listing

## Standart bin files

### All binaries using WLED Wemos shield pinout

- ESP8266 -> LED - GPIO2, GPIO0 - button(or CLK), Relay - GPIO12;
- ESP32 -> LED - GPIO16, GPIO17 - button(or CLK), Relay - GPIO19;
- (for full pinout table, please see schematic)

### Official firmware @Aircoookie repo (top line is newest)

- [v0.11.1_2101130](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.11.1_2101130) - Version 0.11.1 build 2101130
- [v0.11.1_2012210](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.11.1_2012210) - Version 0.11.1 build 2012210
- [v0.91n_2004230](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.91n_2004230) - Version 0.91n build 2004230

### Development bin files @Aircoookie repo

- [v0.12.0-b4_2103281](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.12.0-b3) - Version 0.12.0-b4 build 2103281. First official LED multi pin support.

### Experimental bin files @Blazoncek fork:

- [v0.11.1_2103101 stable](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.11.1_blazoncek_multistrip) - coded by @blazoncek. Included enhanced GUI and LED multi pin strip support with GUI setup.
- [v0.12.0-b4_2103292 development](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.12.0-b4_blazoncek_dev) - coded by @blazoncek. Further development. Added twilightlord-esp32-8MB.bin for great dev board! WARNING!!! Please save your presets.json before updating!