# [ENV]

```
[env:esp32_4ch_fan_display_rotary_relays]
board = esp32dev
platform = espressif32@3.2
board_build.partitions = tools/WLED_ESP32_4MB_1MB_FS.csv
;board_build.partitions = tools/WLED_ESP32_16MB.csv
upload_speed = 460800
monitor_speed = 115200
;upload_protocol = espota
# exchange for your WLED IP
;upload_port = "10.0.0.85"
build_unflags = ${common.build_unflags}
build_flags = ${common.build_flags_esp32}
  -D BTNPIN=0
  -D LEDPIN=2
  -D RLYPIN=-1
  -D IRPIN=-1
  -D WLED_DISABLE_ALEXA
  -D WLED_DISABLE_BLYNK
  -D WLED_DISABLE_CRONIXIE
  -D WLED_DISABLE_HUESYNC
  -D WLED_DISABLE_LOXONE
  -D USERMOD_DALLASTEMPERATURE
  -D TEMPERATURE_PIN=25
  -D USERMOD_FOUR_LINE_DISPLAY # GPIOs: 14, 13, 15, 26, 27
  -D USE_ALT_DISPlAY
  -D FLD_PIN_CLOCKSPI=14
  -D FLD_PIN_DATASPI=13
  -D FLD_PIN_DC=26
  -D FLD_PIN_CS=15
  -D FLD_PIN_RESET=27
  -D USERMOD_ROTARY_ENCODER_UI
  -D ENCODER_DT_PIN=5
  -D ENCODER_CLK_PIN=18
  -D ENCODER_SW_PIN=19
  -D USERMOD_MULTI_RELAY       # GPIOs: 12, 23, 22 & 21
  -D USERMOD_PWM_FAN           # GPIOs: 32, 33
;  -D DEBUG=1
;  -D WLED_DEBUG
;  -DDEBUG_ESP_WIFI
  -UWLED_USE_MY_CONFIG
lib_deps = ${esp32.lib_deps}
  OneWire@~2.3.6
  U8g2@~2.28.8
  ```