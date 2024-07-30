# Arduino-based Car Safety System

This project implements an embedded system for passenger cars to enhance road safety. It uses an Arduino to integrate various sensors and modules for features like geofencing, alcohol detection and emergency alerts.

## Features

- Geofencing with GPS module to reduce horn usage in quiet zones
- Alcohol detection using MQ-3 sensor
- SMS alerts through GSM module
- LED indicators for visual feedback

## Components

- Arduino Uno
- NEO-6M GPS Module
- MQ-3 Alcohol Sensor
- SIM800A GSM Module
- LED
- Buzzer

## Setup

1. Connect the components to the Arduino as per the pin configurations in the code.
2. Upload the respective code files to the Arduino.
3. Power up the system and place it in the vehicle.

## Usage

- The system will automatically reduce horn usage when entering predefined quiet zones.
- If alcohol is detected, it will trigger alerts and potentially send SMS notifications.
- LED indicators provide visual feedback on the system's status.

## Flow diagram:
![flowdiagram](https://github.com/user-attachments/assets/92087b68-18ef-4f04-bf86-a7ed213fb65f)
