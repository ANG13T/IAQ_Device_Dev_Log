---
layout: post
title: Designing a Electrical Schematic
categories: Electronics
---

Today, I made a simple schematic design including the ESP32, MQ135, BME680, and a LED setup for a visual air quality hazard display using EasyEDA (a free online PCB design tool). The I/O pins of the ESP32 will monitor the air quality of the surroundings and send the data to a web server via the ESP32. The red LED indicates dangerous air quality range (ppm > 1500), yellow is cautious air quality (ppm >= 750 & ppm < 1500), and green for good air quality (ppm < 750).

## Pictures
![image](https://github.com/angelina-tsuboi/IAQ_Device_Dev_Log/blob/master/images/IMG_3.png?raw=true)

## Next Steps

I plan to add an O-LED display to the prototype version of the device and schematic. The prototype version of the device will be made using breadboard and jumper wires, but the production version will be condensed down to a PCB board. We are not at the stage to print a PCB yet, so we will continue tinkering with prototype until we get it to work.

Cheers!
Angelina