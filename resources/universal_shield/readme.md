# Universal shield black v3.0

- [Shield pinout](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/Images/wiki/Wemos_shield_pinout.pdf)

## Shield PCBs and scematic

## PCB

![PCB top](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/universal_shield/images/shield-v3.0smd_r2_top.png)


![PCB bottom](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/universal_shield/images/shield-v3.0smd_r2_bottom.png)

## Solder jumpers

- By default shield is preconfigured for use with digital microphone(IO14 and IO15 not shifted);
- Jumpers have to be soldered according to chosen configuration:
- IO1-IO3 - Let you choose D2 output, GPIO1 or GPIO3;
- IO15 (ESP32 only)- Let you choose if your output 15 is shifted or not (side marked "S" is shifted);
- IO15-1 (ESP32 only) - Must be soldered if output 15 is shifted;
- IO14 (ESP32 only) - Let you choose if your output 14 is shifted or not (side marked "S" is shifted);
- IO14-1 (ESP32 only) - Must be soldered if  output 14 is shifted;
- J-R2 - If soldered bypassing resistor R2;
- J-R1 - Soldered if resistor R1 must be used;

## Scematic

[![Schematic](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/universal_shield/images/Schematic_v3.0smd_r2.png)](https://github.com/srg74/WLED-wemos-shield/blob/master/resources/universal_shield/images/Schematic_v3.0smd_r2.pdf)
