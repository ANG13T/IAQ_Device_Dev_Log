---
layout: post
title: Setting up a basic Flask web server on the Raspberry Pi and configuring GPIO inputs
categories: Electronics
---

Today I configured the Raspberry Pi on a spare monitor I found in my house, SSH into the Pi using my laptop, hosted a basic Flask server onto the Pi which included a toggle button to set the 24 pin on the Pi on either HIGH or LOW depending on the state of the toggle, and coded some basic GPIO functionality for the Pi. Unfortunately, the GPIO functionality did not work (I tested a basic LED circuit, but enabling the toggle did not light up the LED), however, I was able to successfully SSH into the Pi and host a web server using Flask.

## Troubleshooting

Some silly mistakes I made today include plugging the HDMI cable for the Raspberry Pi display into a incompatible monitor and forgetting the password for my Raspberry Pi. I reset the password for my Pi using a ```passwd``` command. Moreover, I had trouble setting up a Node.js server due to version complications, so I ended up using Flask instead.


## Pictures
![](https://github.com/angelina-tsuboi/IAQ_Device_Dev_Log/blob/master/images/IMG_1.jpeg)

## Next Steps

In my next tinkering session, I plan to fix the GPIO inputs and start getting inputs from sensors. After that, I will start making the API to connect the device input to the database, do more research on components, and start designing the case / schematic. 

Cheers!
Angelina