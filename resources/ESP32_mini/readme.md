# ESP32 mini dev board


[All docs moved to](https://github.com/srg74/ESP32-mini-SerKo)<a href=https://github.com/srg74/ESP32-mini-SerKo> ➡️</a>

[ESP32 mini board schematic](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/ESP32_mini/Resources/ESP32_mini_board_schematic.pdf)<a href=https://github.com/srg74/WLED-wemos-shield/blob/master/resources/ESP32_mini/Resources/ESP32_mini_board_schematic.pdf> ➡️</a> 

**Platformio build environment:**

```
[env:esp32_16mb]
board = esp32dev
platform = espressif32@3.5
board_build.partitions = tools/WLED_ESP32_16MB.csv
upload_speed = 921600
monitor_speed = 115200
build_unflags = ${common.build_unflags}
build_flags = ${common.build_flags_esp32}
  -D WLED_WATCHDOG_TIMEOUT=0
  -D WLED_RELEASE_NAME=esp32_16mb
  -D SERVERNAME='"WLED-16mb"'
  -D BTNPIN=17
  -D LEDPIN=16
  -D RLYPIN=19
  -D IRPIN=-1
;  -D USERMOD_AUTO_SAVE
  -UWLED_USE_MY_CONFIG
lib_deps = ${esp32.lib_deps}

```
**Arduino board manager entry:**

```
{
"build": {
    "arduino": {
    "ldscript": "esp32_out.ld"
    },
    "core": "esp32",
    "extra_flags": "-DARDUINO_ESP32_DEV",
    "f_cpu": "240000000L",
    "f_flash": "40000000L",
    "flash_mode": "dio",
    "mcu": "esp32",
    "variant": "esp32",
    "partitions": "partitions_16M.csv"
},
"connectivity": [
    "wifi",
    "bluetooth",
    "ethernet",
    "can"
],
"debug": {
    "openocd_board": "esp-wroom-32.cfg"
},
"frameworks": [
    "arduino",
    "espidf"
],
"name": "ESP32 mini board 16MB",
"upload": {
    "flash_size": "16MB",
    "maximum_ram_size": 327680,
    "maximum_size": 16777216,
    "require_upload_port": true,
    "speed": 2000000
},
"url": "https://en.wikipedia.org/wiki/ESP32",
"vendor": "SerKo"
}
```

**Parttiton file for 16mb:**

```
# Name,   Type, SubType, Offset,  Size, Flags
nvs,      data, nvs,     0x9000,  0x5000,
otadata,  data, ota,     0xe000,  0x2000,
app0,     app,  ota_0,   0x10000, 0x200000,
app1,     app,  ota_1,   0x210000,0x200000,
spiffs,   data, spiffs,  0x410000,0xBE0000,
```
