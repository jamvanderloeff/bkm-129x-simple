A simplified version of the BKM-129X compatible board.

Revision A

Should be able to be created at $25-30, with the ADG1611 being the most expensive component.

This requires an Arduino Nano v3 loaded with the latest BKM-129X-MCU code from https://github.com/skumlos/bkm-129x-mcu

For more information go to https://immerhax.com/?p=422

You are welcome to clone, produce and sell hardware based on this. Please keep changes and so on open source.

Cool kids give credit where due.

Thanks goes out to Nick Carney and Bob from RetroRGB for rigorious testing!

--------

Compatibility list and tested consoles (including issues):

PVM-9L2
- SNES (NTSC, CSYNC)
- Mega Drive 2 (PAL, 60 Hz modded with DFO for "true" 60 Hz, CSYNC)
- Master System 1 (PAL, 60 Hz modded with DFO for "true" 60 Hz, CSYNC)

BVM-D14
- Genesis 1 (60 Hz, CSYNC)

BVM-D9
- Nomad (60 Hz, Triple bypass modded, CSYNC)
- Master System (60 Hz, sync issues like original 129X)
- TurboGrafx/PC-Engine (60 Hz, sync issues like original 129X)

---------

Board revision history:

A: Changed R9 to 0 Ohm / jumper

---------

(2020) Martin Hejnfelt (martin@hejnfelt.com)
