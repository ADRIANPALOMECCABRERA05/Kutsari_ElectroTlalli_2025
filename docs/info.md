<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

Simon Says is an interactive memory game where the player must replicate an increasingly complex sequence of colors. The game presents the sequence by illuminating LEDs, each associated with a distinct tone.

At the start of each round, the game displays the current sequence, after which the player must repeat it by pressing the corresponding buttons in the correct order. If the player successfully reproduces the sequence, a "level-up" sound plays, a new color is added to the sequence, and the game advances to the next round.

The game continues until the player makes an error. At that point, a "game over" sound is played, and the sequence resets, allowing the player to start over.

## How to test

## Connections:

Connect the buttons to btn1, btn2, btn3, and btn4, each with a pull-down resistor.
Connect the LEDs to led1, led2, led3, and led4, ensuring each LED matches the color of its corresponding button.
Connect the speaker to the speaker pin for audio feedback.
Connect the 7-segment display as follows:
seg_a through seg_g to the individual segments.
dig1 to the common pin of the tens digit.
dig2 to the common pin of the ones digit.
Set seginv to high for a common anode display or low for a common cathode display.

## Game Operation:
The system initializes in a reset state.
Press any button to start the game.
The game runs on a 50KHz clock input.
Follow the sequence, and enjoy the challenge!

## External hardware

## Required Components:

4 push buttons (preferably in red, green, blue, and yellow).
4 LEDs (matching the button colors).
Resistors (for pull-down and current-limiting purposes).

## Optional Components:
Buzzer or speaker (for sound effects).
Two-digit 7-segment display (to show the score).
