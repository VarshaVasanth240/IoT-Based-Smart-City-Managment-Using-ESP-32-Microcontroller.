# 🏙️ IoT-Based Smart City Management System Using ESP32

An IoT-based Smart City Management System developed using an **ESP32 microcontroller** to integrate smart parking, automatic street lighting, and intelligent waste management into a single system.

The project focuses on improving **parking management, energy conservation, waste disposal monitoring, and user accountability** through sensor-based automation.

---

## 🚀 Project Overview

The system consists of three major smart-city modules:

### 🚗 Smart Car Parking System
Monitors parking spaces and identifies available and occupied parking slots using sensors.

### 💡 Automatic Street Light System
Automatically controls street lights based on ambient light conditions using an LDR sensor.

- 🌙 During night → Street lights ON
- ☀️ During daytime → Street lights OFF

This helps reduce unnecessary electricity consumption.

### 🗑️ Smart Waste Management System
Provides controlled access to the smart dustbin using a password-protected servo mechanism.

The system also monitors waste disposal and identifies incorrect disposal of wet waste in the dry-waste section. A fine is generated for incorrect disposal and the fine details are recorded in an Excel sheet.

---

# 🎯 Objectives

- Develop an IoT-based smart city management system using ESP32.
- Monitor parking-slot availability automatically.
- Automate street lights based on day and night conditions.
- Reduce unnecessary energy consumption.
- Provide secure access to the smart dustbin using password authentication.
- Monitor proper waste segregation.
- Generate fines for incorrect waste disposal.
- Maintain fine records for monitoring and accountability.

---

# 🛠️ Components Used

## Hardware

- ESP32 Development Board
- Ultrasonic Sensors
- LDR Sensor
- Servo Motor
- LEDs / Street Light LEDs
- Buzzer
- Keypad / Password Input
- Waste Detection Sensors
- LCD/OLED Display
- Jumper Wires
- Breadboard
- Power Supply

## Software

- Arduino IDE
- Embedded C / Arduino C
- ESP32
- Sensor-based automation
- Excel for fine record management

---
          IoT-Smart-City-Management/
│
├── Smart_City_Management.ino
├── README.md
│
├── parking/
│   └── parking_code.ino
│
├── street_light/
│   └── street_light_code.ino
│
├── smart_dustbin/
│   └── smart_dustbin_code.ino
│
└── images/
    ├── project-prototype.jpg
    └── circuit-diagram.jpg
     v                                  v
   OCCUPIED                         AVAILABLE
