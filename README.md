# Gas Flame Safety System 🔥

This project is designed to detect **gas leakage** and **flames** in households, labs, or small industries and provides alerts to ensure safety. It helps prevent accidents by immediately notifying users through buzzer and LED indicators.

---

## Table of Contents
1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Components Required](#components-required)
4. [Circuit Diagram](#circuit-diagram)
5. [Working](#working)
6. [Installation / Usage](#installation--usage)
7. [Author](#author)
8. [License](#license)

---

## Project Overview
The Gas Flame Safety System continuously monitors gas levels and detects flames. If any dangerous levels are detected, it triggers a buzzer and LED alerts. The system is controlled using an Arduino microcontroller and is suitable for homes, labs, and small industries.

---

## Features
- Gas leakage detection using MQ2 sensor
- Flame detection using Flame Sensor
- Buzzer and LED alerts
- Real-time monitoring
- Easy integration with Arduino
- Can be extended for automated ventilation or safety shutdown systems

---

## Components Required
- Arduino UNO / Nano
- MQ2 Gas Sensor
- Flame Sensor
- Buzzer
- LEDs
- Jumper wires
- Breadboard / PCB

---

## Circuit Diagram
*(Include your `circuit diagram.jpeg` image here)*

```text
[Arduino] --- [MQ2 Gas Sensor]
[Arduino] --- [Flame Sensor]
[Arduino] --- [Buzzer + LEDs]
Working
MQ2 sensor constantly monitors the surrounding gas levels.

Flame sensor detects any fire or flame nearby.

When dangerous gas levels or flame is detected:

Buzzer sounds to alert the user

LEDs light up to indicate danger

Users can take immediate action to prevent accidents.

Installation / Usage
Connect sensors and buzzer to Arduino according to the circuit diagram.

Upload main.ino to Arduino using Arduino IDE.

Power on the system.

Monitor the system for gas or flame alerts.

Extend the system to control ventilation or safety mechanisms if required.

Author
Mohan Madhukar Jadhav
Email: your-email@example.com
GitHub: https://github.com/mohanjadhav0374