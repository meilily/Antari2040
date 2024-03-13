## Table of contents

- [Overview](#overview)
- [Features](#features)
- [BOM](#bom)
- [Case](#case)
- [Assembly Guide](#assembly-guide)
- [Firmware](#firmware)


## Overview


ANTARI rp2040 is a 3x4 macropad with rotary encoders and BLE support. 

Designer and maintainer: [sandipratama/nendezkombet](https://github.com/nendezkombet) 

![IMG_20240311_163237](https://github.com/nendezkombet/Antari2040/assets/82454371/8820e1d6-5482-40e7-9e75-e3970bcff19c)



## Features

- Easy to source components.
- Easy to build.
- MX style switch and Kailh low profile V2 switch compatible
- Seeeduino xiao rp2040/nrf52840 as main MCU.
- QMK powered.
- RGB support .
- Rotary encoder support.
- Completely open-source.



## BOM

|Parts|Footprint|Quantity|
|:---|:---|:---|
|Sk6812 mini RGB LED |5050|12|
|MX switch |3 or 5 pin|12|
|Hotswap socket |kailh or similiar |12|
|1N4148 diode |SOD-123 or axial|12|
|Rotary encoder|EC11|1|
|Seeeduino Xiao |rp2040/nrf52840|1|
|220ohm resistor|0805 or axial|1|
|Micro slide switch (optional)|MSS22D18 |1|
|3.7v battery (optional) |3mm thick|1|
|6mm M2 "FEMALE TO FEMALE" brass standoff|round |4|
|5mm M2 screw |round |8|



## Case


Stacked acrylic case cutting file can be open with Adobe Illustrator or Corel Draw and ready for cutting process.


## Assembly Guide

See inside cutting file folder !!!


## Firmware


The firmware is fully QMK, see [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) then the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. 


## Firmware flashing :

Drag and drop .uf2 file to pop-up folder after enter bootloader

## Enter the bootloader :

Press the reset button twice on the MCU  


