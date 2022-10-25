# Firmware listing

## Standart bin files

### All binaries using WLED Wemos universal shield pinout

- ESP8266 -> Digital OUT1 - GPIO2, GPIO0 - button, GPIO1 or GPIO3 CLK(or Digital OUT2), Relay - GPIO12;
- ESP32 -> Digital OUT1 - GPIO16, GPIO17 - button, GPIO1 or GPIO3 CLK(or Digital OUT2), Relay - GPIO19;
- [Full WLED Wemos Universal shield pinout](https://github.com/srg74/WLED-wemos-shield/wiki/Pinout)

### Official firmware @Aircoookie repo (top line is newest), also added DEBUG builds

- [v0.14.0-b0](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.14.0-b0) - Version v0.14.0-b0 build 2210251
- [v0.13.3](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.13.3) - Version v0.13.3 build 2210150
- [v0.13.2](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/WLED_wemos_shield/v0.13.2) - Version v0.13.2 build 2208210

### Experimental bin files @Blazoncek fork

- [Moved to experimental](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/experimental) - coded by @blazoncek. Included enhanced GUI and LED multi pin strip support with GUI setup. And many more improvements

```diff
- WARNING!!! Please save your presets.json before updating firmware!
```http://IP_ADDRESS/edit
```
