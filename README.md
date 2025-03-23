# Semi-Automatic Waste Segregator

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Working Principle](#working-principle)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
---

## Introduction
The **Semi-Automatic Waste Segregator** is a system designed to separate waste into wet and dry. It helps in improving waste management, reducing pollution, and encouraging recycling.

This system uses **sensors** to detect and classify waste and an **Arduino-controlled servo motor** to direct the waste into the appropriate bin.

---

## Features
- **Waste classification** into **Wet and Dry** categories.
- **Moisture Sensor** for identifying waste.
- **Servo Motor Mechanism** for directing waste to the correct bin.
- **Microcontroller-based automation** (Arduino Uno).
- **User-friendly system** with somewhat manual intervention.

---

## Hardware Requirements
- **Arduino Uno**
- **Moisture Sensor** (for  waste detection)
- **Servo Motor** (to rotate and direct waste)
- **Power Supply** (Laptop Powered for prototype)

---

## Software Requirements
- **Arduino IDE**
- **C++ / Embedded C**
- **Servo Library** (`Servo.h`)

---

## Working Principle
1. **Waste Detection**  
   - The **Moisture Sensor** detects if the object has moisture.
2. **Sorting Mechanism**  
   - The **Servo Motor** moves accordingly:
     - **Wet Waste** → Directed to **Wet Waste Bin**.
     - **Dry Waste** → Directed to **Dry Waste Bin**

## Usage
1. **Turn ON the System.**
2. **Place Waste Near the Sensor.**
3. **Wait for Classification.**
4. **Observe the Servo Motor Sorting the Waste.**
5. **Check the Bin for Proper Segregation.**



## Future Improvements
- **Integration with AI** for advanced waste detection.
- **Automated Conveyor Belt System** for continuous waste segregation.
- **Mobile App Connectivity** for monitoring waste levels.
- **Solar Power Implementation** for energy efficiency.
