# WLED PlatformIO Builds

This project supports multiple hardware targets and configurations. Below is a summary of the actively defined builds:

---

## Shields Builds

### esp01_1m_full_shield

- **Target:** ESP01 shield (1MB flash)
- **Features:** Minimal build for ESP01 shield, disables several features to fit in 1MB.

### esp8266_mini_shield_minimum

- **Target:** D1 mini board (4MB)
- **Features:** Minimal build for mini shield, disables some features for space.

### esp32_mini_shield_minimum_4mb

- **Target:** ESP32 mini board (4MB)
- **Features:** Minimal build for ESP32 mini shield, disables some features for space.

### esp32_mini_shield_minimum_16mb

- **Target:** ESP32 mini board (16MB)
- **Features:** Minimal build for ESP32 mini shield, disables some features for space.

### esp32_mini_shield_aux_16mb

- **Target:** ESP32 mini board (16MB)
- **Features:** Auxiliary build, includes audio reactive usermod.

### esp8266_universal_shield_minimum

- **Target:** D1 mini board (universal shield)
- **Features:** Minimal build for universal shield, disables some features for space.

### esp32_universal_shield_minimum_4mb

- **Target:** ESP32 mini board (4MB, universal shield)
- **Features:** Minimal build for universal shield, disables some features for space.

### esp32_universal_shield_minimum_16mb

- **Target:** ESP32 mini board (16MB, universal shield)
- **Features:** Minimal build for universal shield, disables some features for space.

### esp32_universal_shield_usermods_4mb

- **Target:** ESP32 board (4MB, universal shield)
- **Features:** Usermods build, includes temperature, four_line_display_ALT, rotary encoder, audioreactive.

### esp32_universal_shield_usermods_16mb

- **Target:** ESP32 board (16MB, universal shield)
- **Features:** Usermods build, includes temperature, four_line_display_ALT, rotary encoder, audioreactive.

---

## ESP32 Dev Board Builds

### esp32_devb_Dallas_sensor_PWM_fan_mods_4mb

- **Target:** ESP32 dev board (4MB)
- **Features:** Dallas temperature sensor, PWM fan usermods.

### esp32_devb_Dallas_sensor_PWM_fan_mods_16mb

- **Target:** ESP32 dev board (16MB)
- **Features:** Dallas temperature sensor, PWM fan usermods.

### esp32_devb_SHT_sensor_PWM_fan_mods_16mb

- **Target:** ESP32 dev board (16MB)
- **Features:** SHT temperature sensor, PWM fan usermods.

### esp32_devb_4ch_fan_display_rotary_relays

- **Target:** ESP32 dev board
- **Features:** PWM fan, temperature, four_line_display_ALT, rotary encoder, multi relay usermods.

---

## ESP32-pico-D4 Board Builds

### esp32_pico_board

- **Target:** ESP32-pico-D4 board
- **Features:** Audio reactive usermod.

### esp32_pico_v3_02

- **Target:** ESP32-pico-v3-02 board
- **Features:** 8MB flash, disables brownout detector.

---

## Manufacturer Hacked Controllers

### sp501e_2mb

- **Target:** ESP8266 2MB board (SP501E)
- **Features:** Disables several features for space, supports up to 3 virtual busses.

### sp511e_2mb

- **Target:** ESP8266 2MB board (SP511E)
- **Features:** Disables several features for space, supports up to 3 virtual busses.

---

## Users Requested/Test Builds

### esp8266_debug

- **Target:** ESP8266 (D1 mini)
- **Features:** Debug build, disables some features, enables debug output.

### esp32_debug

- **Target:** ESP32 dev board
- **Features:** Debug build, includes audioreactive usermod, enables debug output.

### esp8266_dmx

- **Target:** ESP8266 (D1 mini)
- **Features:** DMX support enabled.

### esp8266_PIRmod

- **Target:** ESP8266 (D1 mini)
- **Features:** PIR switch usermod.

### esp8266_staircase_mod

- **Target:** ESP8266 (D1 mini)
- **Features:** Animated staircase usermod, disables several features.

### esp8266_display_rotary

- **Target:** ESP8266 (D1 mini)
- **Features:** Four line display and rotary encoder usermods.

### esp8266_dallas_mod

- **Target:** ESP8266 (D1 mini)
- **Features:** Dallas temperature sensor usermod, disables several features.

### esp32_PIRmod

- **Target:** ESP32 dev board
- **Features:** PIR switch usermod.

### esp32_staircase_mod

- **Target:** ESP32 dev board
- **Features:** Animated staircase usermod.

### esp32_ethernet

- **Target:** ESP32 dev board
- **Features:** Ethernet support enabled, disables several features.

### esp32_dmx

- **Target:** ESP32 dev board
- **Features:** DMX support enabled.

### esp32_bme280

- **Target:** ESP32 dev board
- **Features:** BME280 sensor and four line display usermods.

### esp32_display_rotary_encoder_battery_stat

- **Target:** ESP32 dev board
- **Features:** Four line display and rotary encoder usermods.

### esp32s2_saola_1

- **Target:** ESP32-S2 Saola board
- **Features:** Experimental build for ESP32-S2.

### esp32s3dev_8MB

- **Target:** ESP32-S3 dev board (8MB)
- **Features:** Audio reactive usermod, new FFT, S3-specific settings.

### esp32_stamp5_c3

- **Target:** ESP32-C3 devkit
- **Features:** Audio reactive usermod, SQUELCH and GAIN settings for ICS-4343x.

---

## Notes

- Each build can be selected by specifying the corresponding environment in PlatformIO.
- For custom builds, refer to the comments and usermod documentation for additional configuration options.
