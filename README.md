Final_Project_ECE_383 Final Project - Mario AI
==============================================

For this lab I will be working on a VHDL Nintendo Entertainment System with C2C John Miller and C2C Kevan Mordan. This will include making a VHDL emulator with PPU(picture processing unit) and a ROM loader to emulate a game. It will also include an artificial intelligence to play the game.


Proposal:
=========
Create a system that will :

Be able to take an image of an NES emulator from a laptop screen via VGA
Analyze the image and determine the location of an obstacle on screen
Determine the appropriate move for Mario to perform
Send that command via usb output

Detailed Tasks and Schedule
===========================
Find a working Super Mario Bros. Rom
Figure out how to analyze the VGA signal and interpret the colors ( LSN 35)
Make sure that the data accurately represents the visuals on screen (LSN 35/36)
Create code to correctly identify an obstacles position relative to Mario (LSN 36/37)
Create code to determine the proper action to take (Jump or move forward) (LSN 37)
Be able to interface the FPGA with the USB input on the laptop to actually control Mario (LSN 38)

Functionality Levels
====================

Group:
======
-Required: Mario is able to successfully jump onto the goomba on the first screen
-B: Mario can make it past the first pit obstacle
-A: Mario finishes level 1-1
Me:
===
-Required: Basic processing of an image
-B: Identify where Mario and enemies are
-A: Identify entire environment


Hardware
========
Just a USB controller, the rest is done on the laptop
