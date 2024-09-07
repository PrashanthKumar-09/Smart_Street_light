# Smart Street Light with Cleaning Mechanism

This repository contains the code and documentation for a **Smart Street Light** system using **NodeMCU**, equipped with sensors, a rotating mechanism, and an automatic cleaning feature for the light shield.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Components Used](#components-used)
- [Circuit Diagram](#circuit-diagram)
- [Code Explanation](#code-explanation)
- [How It Works](#how-it-works)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

## Project Overview

This project aims to develop a **smart street lighting system** that enhances energy efficiency and longevity by using sensors and an automatic cleaning mechanism. It adjusts lighting based on real-time conditions and rotates for optimal coverage. The shield, protecting the light, is cleaned periodically to maintain light intensity.

## Features

- **Automatic Brightness Adjustment**: Uses light sensors to detect ambient light and adjust the brightness accordingly.
- **Motion Detection**: Infrared or ultrasonic sensors turn the lights on when movement is detected.
- **Rotating Mechanism**: The light can rotate within a fixed range to cover different areas effectively.
- **Cleaning Mechanism**: The light shield is cleaned periodically using a simple motorized mechanism to remove dust or debris, maintaining light clarity.
- **Low Power Consumption**: Uses energy-efficient components.

## Components Used

- **NodeMCU (ESP8266)**: Microcontroller for controlling the system.
- **Light Dependent Resistor (LDR)**: For detecting ambient light.
- **PIR/Ultrasonic Sensor**: For motion detection.
- **Servo Motor**: For the rotating mechanism.
- **Motor**: For the cleaning mechanism.
- **LED**: Represents the street light.
- **Relay Module**: To control the power of the LED light.
- **Power Supply**: 5V and 12V for NodeMCU and motors.

## Circuit Diagram

(Include the circuit diagram here, or provide a link to the image if hosted elsewhere.)

## Code Explanation

The project code is written in **C++** using the Arduino IDE. Below is a brief explanation of key parts of the code:

- **Sensors Initialization**: Initializes the sensors like LDR and motion sensors to read input values.
- **Motor Control**: Handles the cleaning mechanism and rotating system using Servo and DC motors.
- **Light Control**: Adjusts the brightness of the LED based on the input from the LDR.
- **Conditional Execution**: Activates the light and cleaning mechanism based on conditions like darkness, motion, or time intervals.

## Steps

1. Open the project in Arduino IDE.
2. Connect NodeMCU to your computer via USB.
3. Upload the code to the NodeMCU.
4. Assemble the hardware as per the circuit diagram.

## How It Works

1. The **LDR sensor** detects ambient light and adjusts the brightness of the LED accordingly.
2. When **motion is detected** using the PIR sensor, the light turns on for a predefined time.
3. The **servo motor** rotates the light within a specific range to cover different areas.
4. Periodically, the **cleaning mechanism** activates and cleans the light shield to maintain optimal brightness.
5. The system ensures energy conservation by only using full power when necessary.

## Future Improvements

- **Cloud Integration**: Store sensor data and system performance metrics on the cloud for monitoring and predictive maintenance.
- **Solar Power**: Incorporate solar panels to make the system energy self-sufficient.
- **Mobile App**: Develop a mobile app to control the street light system remotely.
- **Advanced Motion Detection**: Improve motion sensors to distinguish between human and non-human movements.

## Contributors

- **Prashanth** – Lead Developer  
