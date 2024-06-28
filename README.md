# Microcontrollers 

# Introduction
This lab was completed at the University of Texas Rio Grande Valley as part of the EECE 3225 Electrical Engineering Lab 1 course by Juan Cantu and Kaysi Gutierrez during the Spring of 2023.

# Abstract
This lab aimed to enhance understanding of microcontrollers by exploring their structure,
operation, and programming using assembly language. The objectives included observing the
effects of various C statements on microcontroller behavior and measuring different
microcontroller parameters. The lab was divided into three parts, each focusing on a specific
project. Part 1 involved writing a program to generate a pulse train with a specific width and
period on a designated pin. This project utilized NOP() instructions to control the timing and
achieve the desired pulse characteristics.
Part 2 focused on configuring the microcontroller's ports to handle input and output operations.
The program written for this project utilized PORTB as input and PORTD as output. It involved
performing arithmetic operations on two 4-bit numbers (X1 and X2) received via specific pins
and displaying the sum on a seven-segment display. Additionally, if the sum exceeded the
hexadecimal value of F, a dash symbol was displayed. In Part 3, a MOSFET transistor was
employed as a switch to control a motor. The circuit utilized Pin RD0 of the microcontroller to
drive the MOSFET's gate. Two input pins (RB0 and RB1) denoted as AB determined the
microcontroller's behavior. Specifically, four different states were programmed based on AB
values: AB = 00 for motor off, AB = 11 for motor on, AB = 01 for the motor to alternate between
on and off states every 2 seconds, and AB = 10 for generating a pulse train with a 50% high and
50% low duty cycle at a specific frequency.

# Part 1
For this project, we had to write a program that produces a pulse train with the given width and
period on the specified pin. Table 1, below shows the projects with their assigned group letter.
For this lab, we were assigned group ‘B’.

![part1](https://github.com/JuanCantu1/Microcontrollers/assets/109363196/c23029b4-36ed-4746-81ac-3b7b5ad022ef)
