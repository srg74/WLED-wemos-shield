# Development fork @blazoncek

- [v0.15.0-b5 builds](https://github.com/srg74/WLED-wemos-shield/tree/master/resources/Firmware/@blazoncek/latest) - v0.15.0-b5 build 2409230

```text
# Example for a build
[env:esp32_Dallas_sensor_PWM_fan_display_rotary_ambient_light_sensor_sound_mods]
board = esp32dev
platform = espressif32@3.5
upload_speed = 460800
monitor_speed = 115200
;upload_protocol = espota
# exchange for your WLED IP
;upload_port = "10.0.0.94"
build_unflags = ${common.build_unflags}
build_flags = ${common.build_flags_esp32}
  -D WLED_DISABLE_BLYNK
  -D WLED_DISABLE_CRONIXIE
  -D WLED_DISABLE_HUESYNC
  -D WLED_DISABLE_LOXONE
# Enable Ethernet shield
;  -D WLED_USE_ETHERNET
# Pins assigment and pixel count
  -D BTNPIN=0
  -D LEDPIN=2 # Single pin
;  -D DATA_PINS=1,2 # Multiple pins
;  -D PIXEL_COUNTS=150,150,150,150 # Pixel count assigment
  -D IRPIN=-1
  -D RLYPIN=16
# User mods
  # Dallas temperature sensor mod
  -D USERMOD_DALLASTEMPERATURE
  -D TEMPERATURE_PIN=4
  # Display mod
  # I2C display section
  -D USERMOD_FOUR_LINE_DISPLAY
  -D USE_ALT_DISPlAY
  -D FLD_PIN_SCL=22
  -D FLD_PIN_SDA=21
  -D FLD_TYPE=SH1106
;  -D FLD_TYPE=SSD1306
  # SPI display section
  ; -DFLD_SPI_DEFAULT
  ; -D FLD_TYPE=SSD1306_SPI64
  ; -D FLD_PIN_CLOCKSPI=14
  ; -D FLD_PIN_DATASPI=13
  ; -D FLD_PIN_DC=26
  ; -D FLD_PIN_CS=15
  ; -D FLD_PIN_RESET=27
  # Rotary encoder mod
  -D USERMOD_ROTARY_ENCODER_UI
  -D ENCODER_DT_PIN=18
  -D ENCODER_CLK_PIN=19
  -D ENCODER_SW_PIN=17
  # Multirelay mod
  ; -D USERMOD_MULTI_RELAY  # 12, 23, 22 & 21
  # PWM Fan mod
  -D USERMOD_PWM_FAN
  -D PWM_PIN=32
  -D TACHO_PIN=33
  # Ambient light sensor BH1750
  -D USERMOD_BH1750
  -D USERMOD_BH1750_FIRST_MEASUREMENT_AT=30000
  -D USERMOD_BH1750_MAX_MEASUREMENT_INTERVAL=60000
;  -D USERMOD_BH1750_MIN_MEASUREMENT_INTERVAL=10000
;  -D USERMOD_BH1750_OFFSET_VALUE=2
  # Sound reactive usermod
  -D USERMOD_AUDIOREACTIVE
;  -D WLED_DEBUG
  -UWLED_USE_MY_CONFIG
lib_deps = ${esp32.lib_deps}
  U8g2@~2.32.15 # Uncoment for display mod
  paulstoffregen/OneWire@~2.3.6 # Uncoment for temperature mod
  claws/BH1750 @ ^1.3.0 # Uncoment for light sensor mod
  https://github.com/blazoncek/arduinoFFT.git
board_build.partitions = ${esp32.default_partitions}
```

## 🔴 Please, test latest firmware and report any issue to WLED Discord. Help highly anticipated and appreciated! 🔴
