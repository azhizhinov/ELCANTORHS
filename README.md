## El Cantor HS
![El Cantor HS](/Pictures/20231122.AZHIZHINOV.ELCANTORHS.00.png)
The El Cantor HS keyboard is a 44 key diodeless split keyboard with support for hotswap sockets, designed with simplicity in mind. It is based on the popular [cantor](https://github.com/diepala/cantor), which is inspired on the popular [corne](https://github.com/foostan/crkbd), [ferris](https://github.com/pierrechevalier83/ferris) and [sweep](https://github.com/davidphilipbarr/Sweep) keyboards, aiming to provide a more ergonomic (stronger column stagger) corne-like layout with a simple, easy to assemble and cheap design.
This is a WIP, you can follow the [Cantor's build guide](https://github.com/diepala/cantor/blob/main/doc/build_guide.md), as it is quite similar!

## Thanks
Big thanks to [@Excellenze11](https://github.com/Excellenze11) for ideas, cooperation and tests.

## Parts
As for the parts list, you will need:
- 2x PCB (The left and right half are the same)
- 44 Chocv1 Keys
- 44 Chocv1 Keycaps
- 44 Hotswap sockets for Chocv1 (optional)
- 2x TRRS jacks (PJ-320A)
- 2x Blackpill microcontrollers (STM32F401CC)

## Gerbers
You can find the Gerber files needed to order the PCB on the `Gerbers` directory. Look for the .zip of whatever version you would like!

## Firmware
Firmware for this keyboard is in the QMK tree. You can find sources in this [path](https://github.com/qmk/qmk_firmware/tree/master/keyboards/elcantorhs). You can see/change the layout [here](https://config.qmk.fm/#/elcantorhs/LAYOUT).

## Attention
I'm a hobbyist/amateur at best. So there may be things that aren't optimized. So if you decide to use this, then please be advised that I'm not providing any sort of liability and you should exercise some caution. Use these file for your own risk. Thanks Sebastian Stumpf for this text.
