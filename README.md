# [LG Gram 14Z90N Hackintosh](https://www.lg.com/us/laptops/lg-14Z90N-VAR52A5)

This EFI based mainly on [17z90N](https://github.com/AskDavis/LG-Gram-17Z90N) repository. Thanks @AskDavid.
## Opencore Version: 0.7.0
| Specification       | Details                                 |
| ------------------- | --------------------------------------- |
| OS                  | Catalina              |
| Model               | LG gram 14 - 2020 (14Z90N)              |
| Processor           | Intel Core i5-1035G7                    |
| Integrated Graphics | Intel® Iris® Plus                       |
| Memory              | 16GB RAM & 512GB SSD                    |
| Sound Card          | ...@TODO...                             |
| Wireless Card       | ...@TODO...                             |


## Instructions
### 1. BIOS Settings
- Hold F2 to enter BIOS on boot up
- Press CTRL-ALT-F7 to open Advanced Options
- Main - Boot Features - Quick Boot => Disabled
- Advanced - Intel Advanced Menu - CPU Configuration - Software Guard Extentsions (SGX) => Disabled
- Advanced - Intel Advanced Menu - Power & Performance - "CPU - Power Management Control" - CPU Lock Configuration - CFG Lock => Disabled and Overclocking Lock => Disabled 
- Advanced - Intel Advanced Menu - System Agent (SA) Configuration - Graphics Configuration - DVMT Pre-Allocated => 64M
- Advanced - Intel Advanced Menu - Platform Settings - System Time and Alarm Source => Legacy RTC
- Exit - Exit Saving Changes
### Working
- WIFI
- Sound
- Graphics Acceleration
- Keyboard
- Webcam
- FN keys for audio volume

### Partial working
- Trackpad (not show in system pref)

### Not tested
- Bluetooth
- Thunderbolt / USB C

### Not Working
- HDMI
- Battery Settings
- FingerPrint Reader
- FN keys for brightness

### Installation note
- If stucks at magic/keyboard connect screen, plugin external mouse then install.

## Credits
- Thanks [Opencore community](https://github.com/acidanthera/OpenCorePkg)
- Thanks [AskDavis](https://github.com/AskDavis/LG-Gram-17Z90N)
