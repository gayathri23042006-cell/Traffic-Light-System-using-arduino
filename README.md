# Traffic Light System

## Overview

This project implements a Traffic Light Control System using Embedded C. The system simulates the operation of a real-world traffic signal by controlling Red, Yellow, and Green LEDs in a predefined sequence with specific time delays.

## Features

* Automatic traffic light operation
* Sequential switching of Red, Yellow, and Green LEDs
* Simple and efficient Embedded C code
* Easy to understand and modify
* Suitable for learning microcontroller interfacing

## Components Required

1. Microcontroller Development Board
2. Red LED
3. Yellow LED
4. Green LED
5. 220Ω Resistors (3 Nos)
6. Breadboard
7. Jumper Wires
8. Power Supply / USB Cable

## Circuit Connections

* Red LED → Microcontroller Output Pin
* Yellow LED → Microcontroller Output Pin
* Green LED → Microcontroller Output Pin
* LED Cathodes connected to GND through resistors

## Working Principle

1. Red LED turns ON and remains active for a specified duration.
2. Red LED turns OFF and Yellow LED turns ON for a short duration.
3. Yellow LED turns OFF and Green LED turns ON.
4. Green LED remains active for a specified duration.
5. Green LED turns OFF and Yellow LED turns ON before switching back to Red.
6. The cycle repeats continuously.

## Software Requirements

* Embedded C Compiler
* Microcontroller IDE
* Programmer/Debugger Tool

## Project Structure

```
Traffic-Light-System/
│
├── main.c
├── README.md
└── circuit_diagram.png
```

## Applications

* Traffic Signal Simulation
* Embedded Systems Learning
* Educational Projects
* Microcontroller Training

## Future Enhancements

* Pedestrian Crossing Button
* Vehicle Density Detection
* Smart Traffic Management
* IoT-Based Traffic Monitoring

## Author

Gayathri

## License

This project is intended for educational and learning purposes.
