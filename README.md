# LPC812 Simple Breakout

This is a near-minimal breakout board for LPC812 microcontroller (SOIC-20W variant, LPC812M101JD20).
MCU has ARM Cortex-M0+ core (30MHz), 16KiB flash, 4KiB RAM. Supply voltage 1.8V - 3.6V.

Breakout board includes:
* All 20 pins.
* Decoupling capacitor (805).
* RESET button with pull-up resistor.
* ISP button with pull-up resistor,
  * must be held during reset (released shortly after) to enter bootloader mode,
  * activates USART (PIO0_0 = RXD, PIO0_4 = TXD) for programming.

## Schematic 

TODO: picture

## Layout

TODO: picture

## Toolchain setup

TODO

## Programming (uploading firmware)

TODO

## Blink example

TODO
