# Microwave Oven Simulation

An embedded system project developed using the PIC16F877A microcontroller to simulate the basic operation of a microwave oven. The system provides user interaction through a matrix keypad and displays operating information on a CLCD.

## Features

- Simulates microwave oven operation
- Provides multiple operating modes
- Accepts user input through a matrix keypad
- Displays cooking time and status on CLCD
- Implements countdown timing
- Handles time-based operations using timers and interrupts
- Provides start, stop, and control functionality

## Modules Used

- CLCD
- Matrix Keypad
- Microwave Oven Control
- Timers
- ISR
- Main Application

## Microcontroller

- PIC16F877A

## Technologies Used

- Embedded C
- MPLAB X IDE
- XC8 Compiler
- PIC Microcontroller Programming

## Working

The user selects the required microwave operation using the matrix keypad. The selected mode, cooking time, and operating status are displayed on the CLCD.

Timers and interrupt service routines are used to manage time-dependent operations such as the cooking countdown. The main application coordinates the keypad input, display, timer, and microwave control logic.

## Output

The project simulates the operation of a microwave oven and demonstrates keypad-based control, CLCD interfacing, timer operations, and interrupt handling.
