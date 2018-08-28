# ZX80/ZX81 for MISTer

Port of MiST version by Szombathelyi Gyorgy

### Features:
- Based on Grant Searle's [ZX80 page](http://searle.hostei.com/grant/zx80/zx80.html)
- Selectable ZX80/ZX81
- 16k/32k/64k RAM packs
- YM2149 sound chip (ZON X-81 compatible)
- Sinclar type joystick (keys 67890)
- PAL/NTSC timings
- Turbo loading of .o and .p files
- CHR$128/UDG

### Install
copy *.rbf to the root of SD card.

### Tape loading
Selecting an .o (ZX80) or .p (ZX81) file opens the tape. This is indicated by the
user LED. The LOAD command will load it as it would be on a standard tape.
Reset (ALT-F11 or the Reset OSD option) closes the .o or .p file.