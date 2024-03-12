## Table of contents

- [Overview](#overview)
- [Features](#features)
- [BOM](#bom)
- [Case](#case)
- [Assembly Guide](#assembly-guide)
- [Firmware](#firmware)


## Overview


ANTARI is 3x4 macropad with rotary encoders. The rotary encoder also outputs midi signal when the keyboard is switched to 'Lightroom' dedicated layer, once you pressed an letter key the knob will output a midi cc signal with different parameter, which allows you use a knob to adjust up to 45 sliders in lightroom with Lightroom keymap, most importantly, the value will not jump or jitter, oppositely it moves relatively and smoothly. The oled screen will show you the last letter key you pressed and every information you need. For detailed demo you can visit my youtube [video](https://www.youtube.com/watch?v=S6qfb3bq990&t=147s&ab_channel=Synthvestigator).


Designer and maintainer: [sandipratama/nendezkombet](https://github.com/nendezkombet) 


![DSC04814](https://user-images.githubusercontent.com/82454371/150683198-763633a3-3cf9-430c-b591-c8792491a326.jpg)


![DSC04928](https://user-images.githubusercontent.com/82454371/150683229-19ea3598-54ea-492d-80c4-f1207aff4052.jpg)


![DSC04907](https://user-images.githubusercontent.com/82454371/150683426-ec4313ed-1113-466e-a5df-8ba9de567542.jpg)


![DSC04946](https://user-images.githubusercontent.com/82454371/150683489-f00e6025-abc8-47e6-862c-dd597199564c.jpg)



## Features


- Cheap to build.
- Easy to source components.
- Easy to build.
- MX style switch and Kailh low profile V2 switch compatible
- Rpi Pico powered.
- QMK compatible.
- RGB support .
- Rotary encoder support.
- Completely open-source.



## BOM

|Parts|Footprint|Quantity|
|:---|:---|:---|
|Sk6812 mini RGB LED |5050|12|
|MX switch |3 or 5 pin|16|
|1N4148 diode |SOD-123 or axial|12|
|Rotary encoder|EC11|1|
|Seeeduino Xiao |rp2040/nrf52840|1|
|220ohm resistor|0805 or axial|1|
|Micro slide switch (optional)|MSS22D18 |1|
|3.7v battery (optional) ||1|
|6mm M2 "FEMALE TO FEMALE" brass standoff|round |4|
|5mm M2 screw |round |8|



## Case


Stacked acrylic case cutting file can be open with Adobe Illustrator or Corel Draw and ready for cutting process.


## Assembly Guide

See inside cutting file folder !!!


## Firmware


The firmware is fully QMK, see [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) then the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. 


## Firmware flashing :

Open QMK Toolbox and locate The .hex file you compiled before or use ready flash default keymap

## Enter the bootloader :

Press the button twice on the back of the PCB than hit flash 


