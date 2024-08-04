# Interconnected-Digital-Clock-and-Calendar-System-VS-code-ARM-
Design of a system where two microcontrollers (MCU1 and MCU2) with identical components and functionality can control each other's LCD display to set and display time, date, and operate a stopwatch using UART communication. 

This repository presents an educational project where two microcontrollers (MCU1 and MCU2) each feature a digital clock, stopwatch, and calendar. Each microcontroller has a set of buttons that can control the other's LCD display and functionality via UART communication. This project demonstrates basic embedded systems concepts, including UART communication and interfacing with LCDs.

Project Overview
The system consists of two microcontrollers, each with:

Push buttons for user inputs (setting time, setting date, controlling the stopwatch).
An LCD display for showing time, date, and stopwatch information.
A UART module for communication with the other microcontroller.
This setup allows users to interact with and control the display and functions on the opposite microcontroller, emphasizing the fundamentals of UART communication and basic interfacing techniques.

Features
Time and Date Setting:
Users can set the current time and date using the buttons on one microcontroller, and the changes will be displayed on the other microcontroller's LCD.

Stopwatch Functionality:
The system includes functionalities for starting, stopping, and resetting a stopwatch. Each microcontroller can control the stopwatch display on the opposite microcontroller.

Bidirectional Control:
Each microcontroller's buttons control the other's display and functions, providing a practical demonstration of UART-based communication and control in embedded systems.

Components
Hardware:

Two microcontrollers (e.g., STM32, Arduino, etc.)
LCD displays for each microcontroller
Push buttons for input
UART communication interface
Software:

Firmware for each microcontroller to handle button inputs, LCD updates, and UART communication.
Getting Started
Prerequisites
Hardware:
Two compatible microcontroller development boards, each equipped with an LCD display, buttons, and UART capabilities.

Software:

Development environment for the microcontrollers (e.g., STM32CubeIDE for STM32, Arduino IDE for Arduino).
Necessary drivers and libraries for LCD and UART communication.
