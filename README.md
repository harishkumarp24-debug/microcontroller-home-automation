# Smart Home Automation System 🏠⚡

An ESP8266-powered smart home automation and security system designed for real-time monitoring, intelligent control, and enhanced home safety through an interactive cyber-inspired web interface.

## ✨ Key Features

- Secure login-based web dashboard for authorized access
- Real-time monitoring of temperature and lighting conditions
- Ultrasonic sensor based intrusion detection with buzzer alerts
- Servo motor powered smart door locking mechanism
- PWM-based fan speed regulation for efficient environmental control
- Live device status updates through a responsive web interface

---

## 🔧 Hardware Components

- ESP8266 NodeMCU / Wemos D1 Mini
- HC-SR04 Ultrasonic Sensor
- LM35 Temperature Sensor
- MG90S Servo Motor
- DC Fan with PWM control
- 5V Buzzer
- LEDs / Relay Module

---

## 📍 GPIO Configuration

| Component | Pin | Purpose |
|---|---|---|
| Light Control | D0 | Smart Lighting |
| LM35 Sensor | A0 | Temperature Monitoring |
| Buzzer | D4 | Security Alert |
| Ultrasonic Sensor | D5 / D6 | Distance & Intrusion Detection |
| Fan Control | D7 | PWM Fan Regulation |
| Servo Motor | D8 | Smart Door Lock |

---

## 💻 Software Stack

### Technologies Used
- Arduino C++
- HTML5
- CSS3
- JavaScript

### Libraries
- ESP8266WiFi.h
- ESP8266WebServer.h
- Servo.h

---

## ⚙️ Installation & Setup

1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/smart-home-automation.git
