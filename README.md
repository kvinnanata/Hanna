# kvinnanata-VGA-Edition

PicoMiteVGA V5.07.22

This repository contains the files needed to build the PicoMite VGA Edition

Use all the files from the PicoMite repository with the exception of 
gui.c, 
gui.h, 
touch.c, 
touch.h, 
and CMakeLists.txt

Then build with the two additional files here and the VGA version of the CMakeLists.txt build file

Special thanks to Miroslav Nemecek for the code used as the basis of the 320x240 16colour and 640x480 monochrome VGA drivers. This runs exclusively on the second processor and has little of no impact on MMbasic performance.

Files are included for two designs of PCB specifically designed for this software. The .eprj files are the EasyEDA design files.
V1.0 uses a RLC filter for PWM audio. V1.1 uses a MCP4822 DAC for audio. The BOM include all parts to make the PCBs and are compatible with JLC. To reduce cost you can omit components (e.g. Header pins, RTC clock chip, PS2 section) as required
