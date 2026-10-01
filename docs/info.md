<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

A 3-bit input (A, B, C) is decoded into the seven segments (a–g) of a 7-segment display using only basic logic gates. Each of the 8 input combinations lights up one letter, and stepping through them in order spells "EVARISTO".

## How to test

Set the inputs with the switches: ui_in[0] = A, ui_in[1] = B, ui_in[2] = C. Count from 000 to 111 (A is the lowest bit), and the display should show E, V, A, R, I, S, T, O.

## External hardware

It uses the demo board's DIP switches and 7-segment display (segments a–g on uo_out[0]–uo_out[6]).
