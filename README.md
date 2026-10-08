# ♻️ SwachhPath – Smart Waste Management System

SwachhPath is an IoT-based Smart Waste Management System designed to monitor dustbin fill levels, automate the dustbin lid, and display real-time waste information on a web dashboard.

The system uses an **ESP32**, **ultrasonic sensors**, **servo motor**, **buzzer**, and **Firebase Realtime Database** to collect and display live dustbin information.

---

## 🚀 Features

- 📊 Real-time dustbin fill-level monitoring
- 📡 ESP32-based IoT system
- 📏 Ultrasonic sensor for waste-level detection
- 🤖 Automatic dustbin lid using servo motor
- 🔔 Buzzer alert when the dustbin becomes full
- ☁️ Firebase Realtime Database integration
- 🌐 Web-based monitoring dashboard
- 📍 Dustbin location display using map
- 🚨 Full / Almost Full / Partially Filled status
- 📱 Waste collection notification system
- 🔄 Live sensor data synchronization

---

## 🛠️ Technologies Used

### Hardware
- ESP32 Development Board
- HC-SR04 Ultrasonic Sensors
- Servo Motor
- Buzzer
- Breadboard
- Jumper Wires
- Resistors

### Software
- HTML
- CSS
- JavaScript
- Firebase Realtime Database
- Arduino IDE
- ESP32

---

## ⚙️ How It Works

The system follows this workflow:

```text
Ultrasonic Sensors
        ↓
      ESP32
        ↓
   Wi-Fi Connection
        ↓
Firebase Realtime Database
        ↓
 Web Dashboard
        ↓
Real-Time Monitoring
