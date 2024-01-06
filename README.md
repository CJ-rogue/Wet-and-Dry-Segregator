# Wet and Dry Segregator Arduino Project
Tinkercad: [https://www.tinkercad.com/things/jFRI0uPLUwK-wet-and-dry-segregator](https://www.tinkercad.com/things/jFRI0uPLUwK-wet-and-dry-segregator)

Youtube: 


![image](https://github.com/CJ-rogue/Wet-and-Dry-Segregator/assets/137157404/80882d67-fc29-403b-93cc-7d3e5e1ec662)

## Table of Contents:
1. [Introduction](#introduction)
2. [Components](#components)
2. [Schematic](#schematic)
4. [How It Works](#how-it-works)
5. [Setup](#setup)
6. [Usage](#usage)
7. [Project Team](#project-team)
8. [Disclaimer](#disclaimer)
9. [License](#license)
   
## Introduction
- A Simple College project on waste segregation using Arduino.
- Utilizes Arduino sensors and a Servo Motor for real-time sorting.
- Designed for hands-on learning in electronics and automation.

## Components
    - Arduino Uno or Nano
    - Ultrasonic sensor (HC-SR04)
    - Soil Moisture sensor
    - LCD Display (LCD1602 +IIC-Blue)
    - Servo Motor (MG90S)
    - Jumper Wires
    - Divided waste box with sliding mechanism

## Schematic
**Tinkercad Link**
[Wet and Dry Segregator](https://www.tinkercad.com/things/jFRI0uPLUwK-wet-and-dry-segregator)

![image](https://github.com/CJ-rogue/Wet-and-Dry-Segregator/assets/137157404/a6c510d3-e6c3-464b-bbb5-30667b1756e7)

  
## How it Works
1. **Trash Detection**: The Ultrasonic sensor detects the presence of trash within a specified range.
2. **Moisture Classification**: The Soil Moisture sensor determines whether the detected trash is wet or dry.
3. **Visual Feedback**: The LCD Display provides real-time notifications about the detected trash.
4. **Automated Segregation**: The Servo Motor slides the trash into the corresponding compartment based on its moisture classification.

## Setup
1. Connect the components as per the schematic.
2. Upload the provided Arduino code to the Arduino Uno.
3. Ensure the hardware setup includes a divided box for wet and dry waste, with a Servo Motor for automated segregation.

## Usage
1. Power on the Arduino Uno.
2. Place trash on the soil sensor to initiate the segregation process.
3. Observe the LCD Display for real-time notifications and the Servo Motor's movement as it slides the trash.

## Project Team
- [CJ-rogue](https://github.com/CJ-rogue)
- [Jhnyx](https://github.com/)
- [rhey1235](https://github.com/rhey1235) 

## Disclaimer
This project is developed for educational purposes and may require customization for specific use cases.

## License
This project is licensed under the terms of the [MIT License](LICENSE).
