---
title: FPGA Driven VGA Video Game
date: 2017-12-13
tags: fpga, vga, programming, hardware
--- 

The goal of this project was to create a simple video game, but with all the logic implemented in hardware! This project was a big challenge for me since I am a big software guy and debugging hardware requires to think in terms of hardware, something I am not used to do. After many long hours of sitting in front of my screen, holding my head between my hands in despair because I could not figure out the cause of an error, I learned that when you write VHDL (or any other hardware description language) not only do you have to think about the logic you want to implement but you also about how the physical wires and gates will end up being connected. Otherwise, if you are coming from a mainly software background like me, you start impementing like you would implement software which results in a lot of problems :wink:.

## The Setup
As mentioned before, the video game logic will be implemented in hardware with the help of VHDL, a hardware description language. The actual hardware will consist of an FPGA development board with buttons and a VGA output connected to a LCD screen.

## The approach
