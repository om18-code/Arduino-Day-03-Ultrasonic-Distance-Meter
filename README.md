# 🚀 Day 3 - Ultrasonic Distance Meter

## Overview

This project demonstrates how to measure distance using the **HC-SR04 Ultrasonic Sensor** with an **Arduino Uno**. The measured distance is displayed in real time on a **16×2 I2C LCD** and also printed to the Serial Monitor.

## Features

✅ Real-time distance measurement

✅ Display distance on 16×2 I2C LCD

✅ Serial Monitor output

✅ Accurate distance calculation using ultrasonic waves

✅ Beginner-friendly Arduino project

## Components Used

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* 16×2 LCD with I2C Module
* Breadboard
* Jumper Wires

## Circuit Connections

### HC-SR04

| HC-SR04 Pin | Arduino Uno |
| ----------- | ----------- |
| VCC         | 5V          |
| GND         | GND         |
| TRIG        | D9          |
| ECHO        | D10         |

### 16×2 I2C LCD

| LCD Pin | Arduino Uno |
| ------- | ----------- |
| VCC     | 5V          |
| GND     | GND         |
| SDA     | A4          |
| SCL     | A5          |

> **Note:** If the LCD doesn't display anything, try changing the I2C address from **0x27** to **0x3F**.

## Libraries Required

* Wire Library
* LiquidCrystal_I2C Library

Install the **LiquidCrystal_I2C** library from the Arduino IDE Library Manager.

## Learning Outcomes

* Ultrasonic Sensor Interfacing
* Distance Measurement
* I2C LCD Interfacing
* Serial Communication
* Real-Time Data Display

## Project Output

The project demonstrates:

* Real-time distance measurement
* Distance displayed on the LCD
* Live distance monitoring through the Serial Monitor

## Future Improvements

* Obstacle Detection Alarm using Buzzer
* Distance Limit Warning
* OLED Display Version
* Automatic Parking Assistant
* Smart Distance Monitoring System

## Author

Om Bhagat

## LinkedIn Series

This project is part of my Arduino, Embedded Systems, and IoT learning journey where I build and share projects regularly to strengthen my practical skills.
