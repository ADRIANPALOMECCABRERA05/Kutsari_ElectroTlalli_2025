<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

State machine that implements a typical Austrian traffic light: Red ->
Red+Yellow -> Green -> Green Blinking -> Yellow -> Red. Generated using
a hacked-together Verilog->Wokwi flow :D.

## How to test

Starts in ‘error’ mode (yellow blinking). Switch SW1 (reset) to 1 and back to 0
to start operation. ‘error’ mode can be reached by toggling SW2.

## External hardware

 2 red LEDs, 2 yellow LEDs, 2 green LEDs and current limiting resistors

