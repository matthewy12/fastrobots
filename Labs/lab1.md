<!-- layout: page
title: "lab1"
permalink: https://matthewy12.github.io/fastrobots/Labs/lab1 -->

## Lab 1: The Artemis board

### Objective:
In this lab I downloaded and installed the Arduino IDE on my computer and setup 
the Sparkfun RedBoard Artemis Nano. After using a  USB-C to USB-C cable to connect 
thee Artemis Nano to my computer, I ran example programs to test the functionality 
of the Artemis Nano.

### Parts Required:
1 Sparkfun RedBoard Artemis Nano  <br>
1 USB-C to USB-C cable

### Examples


**1 - Blink it Up**  <br>
For the first example, I uploaded the code from "Blink" which was an example program from Arduino.
It made the Artemis Nano blink a blue light form it's LED by changing the state of it every second.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=wUHbrNhLq_I
" target="_blank"><img src="http://img.youtube.com/vi/wUHbrNhLq_I/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="264" height="198" border="10" /></a>


**2 - Serial**  <br>
I uploaded the code from "Example_04 Serial," an example program in Arduino from which you can see 
information in the serial monitor.
This checks that the serial communication on the Artemis Nano works; we test it by typing in the serial
monitor and seeing that the Artemis Nano echoes it back.
Note: Had to change the baud ratee to 115200 to match the example code.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=J-MSXkMCScc
" target="_blank"><img src="http://img.youtube.com/vi/J-MSXkMCScc/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="264" height="198" border="10" /></a>

**3 - Analog Read**  <br>
I uploaded the code from "Example02_AnalogRead," an example program in Arduino from which you can see
gradual changes in the temperature displayed in the serial monitor. This is done as analogRead is used 
to change the intensity of the LED to match the analog pin's read. As seen in the video, when the 
chip was warmed by hand, the values of the temp displayed in the serial monitor gradually rose.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=KX2a_wdO4iY
" target="_blank"><img src="http://img.youtube.com/vi/KX2a_wdO4iY/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="264" height="198" border="10" /></a>

**4 - Microphone Output**  <br>
The last thing we tried was uploading the code from "Example1_MicrophoneOutput," an example program
from Arduino that shows the usage of the pulse density microphone (PDM). As seen in the video, when the 
Artemis Nano picks up no frequencies when its surroundings are silent, the "Loudest frequency" in the serial 
monitor shows as 0. However, when I whistle at high and low frequencies, the "Loudest frequency" changes reactively and accordingly.

<a href="http://www.youtube.com/watch?feature=player_embedded&v=PnzEpKTJZ9c
" target="_blank"><img src="http://img.youtube.com/vi/PnzEpKTJZ9c/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="264" height="198" border="10" /></a>

[Back to Home](https://matthewy12.github.io/fastrobots/)


