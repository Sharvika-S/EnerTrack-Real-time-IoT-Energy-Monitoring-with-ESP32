# EnerTrack-Real-time-IoT-Energy-Monitoring-with-ESP32(Ongoing Project)


This project is an IoT-based energy monitoring system using the **ESP32 microcontroller** to measure **voltage, current, and power** in real-time. It features an **OLED display** for local monitoring, **automatic relay control** for overload protection, and **Firebase Realtime Database** integration for cloud-based remote monitoring and analytics.

---

## 🔧 Features

- Real-time monitoring of Voltage, Current, and Power using ACS712 and voltage divider
- Automatic relay cutoff in case of overload condition
- OLED (I2C) display for local visualization
- Data logging to Firebase Realtime Database
- Remote control and monitoring via internet (mobile/PC dashboard)
- Expandable for ML-based energy optimization and alerting

---

## 🛠️ Hardware Components

| Component              | Description                      |
|------------------------|----------------------------------|
| ESP32 Dev Module       | Main microcontroller             |
| ACS712 Current Sensor  | Current measurement              |
| Voltage Divider Circuit| Voltage measurement              |
| Relay Module           | Load control                     |
| OLED Display (I2C)     | Local display                    |
| Breadboard + Jumper Wires| Connections                  |

---
📦 Required Libraries
Install in Arduino IDE:

FirebaseESP32 by Mobizt

Adafruit SSD1306

Adafruit GFX

WiFi and Wire (built-in)
---
🔍 Use Case
Smart homes for real-time appliance monitoring

Remote energy analytics

Automated cutoff for overload protection

Expandable to include ML prediction or energy optimization
