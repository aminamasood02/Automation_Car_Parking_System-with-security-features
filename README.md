# Automatic Car Parking System with Security Features

## 📌 Overview
The **Automatic Car Parking System with Security Features** is an embedded system project designed to automate vehicle parking and enhance security in parking lots.  
It uses **Arduino**, **IR sensors**, **motion sensors**, **I2C camera module (OCR)**, and **servo motors** to detect, control, and monitor vehicles entering and leaving the parking area.  
The system automatically opens/closes the parking gate, detects available parking slots, and verifies vehicle number plates for security purposes.

## 🎯 Features
- **Automatic Entry & Exit Gate** using servo motors.
- **IR Sensors** for detecting vehicle presence.
- **Motion Sensors** for enhanced security.
- **I2C Camera Module (OCR)** for number plate recognition.
- **Slot Availability Display** to inform drivers about free spaces.
- **Automatic Gate Locking** in case of unauthorized access.
- **Data Logging** of vehicles entering and exiting.


## 🛠 Hardware Requirements
- Arduino Uno / Mega
- IR Sensors
- Motion Sensor (PIR)
- Servo Motors
- I2C Camera Module with OCR functionality
- LCD Display
- Buzzer
- Jumper Wires & Breadboard
- Power Supply


## 💻 Software Requirements
- Arduino IDE
- OCR Processing Library
- Serial Monitor for debugging
- Optional: Cloud/Database integration for logging data


## ⚙️ Installation & Setup
1. **Assemble the Circuit**
   - Connect IR sensors to detect vehicle presence at entry and exit.
   - Connect servo motor to the Arduino for controlling the parking gate.
   - Install the camera module for number plate recognition.
   - Add the motion sensor for detecting unauthorized activity.
2. **Upload the Code**
   - Open `parking_system.ino` in Arduino IDE.
   - Install required libraries.
   - Upload the code to Arduino.
3. **Power the System**
   - Use a 9V battery or external power supply.
4. **Test the Sensors & Motors**
   - Ensure all sensors detect correctly and servo motors operate smoothly.


## 🚗 How It Works
1. **Vehicle Detection**
   - IR sensor detects the arrival of a vehicle.
2. **Security Check**
   - OCR camera captures and verifies the vehicle number plate.
3. **Gate Operation**
   - Servo motor opens the gate for authorized vehicles.
4. **Slot Management**
   - Available slots are displayed on the LCD.
5. **Exit Process**
   - When leaving, the system repeats detection and verification before opening the gate.


## 📂 Project Structure
