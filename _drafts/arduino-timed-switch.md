---
layout: post
title: Turning off my dryer
tags: arduino
---

### Parts List

3x Green LEDs
3x 180 Ohm resistors
1x 240v AC - 12v DC power pack
1x Arduino
1x Relay Module
2x Momentory Push Buttons
1x 3m Extension lead
1x Project box
Hookup wire
Cable ties
2 sided tape

### Tools

Wire Stripper
Soldering Iron
Dremmel




### Push Buttons

Input is provided by two simple momentory push buttons. Each button is connected from one of Arduino's digital pins to ground, The digital pin is set to OUTPUT and the voltage is set to HIGH, this allows check the current state of the button by doing a digitalRead(). If the button is held down the output will go straight to ground and digitalRead() will return LOW, else digitalRead() will return HIGH.

We can now tell if a button if a button is currently down or currently up but it would be more useful to know if the button has been pressed, where pressed means the button has been held down then released. To do this we need to keep track of the previous state of the button, then if the 

we must check the button at least once between it being pressed and released.

cheap button may register false button presses.

counting presses

### LEDs

making holes for leds would have been much easier with the correct size drill bit







