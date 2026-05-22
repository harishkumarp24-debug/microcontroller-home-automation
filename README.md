# Smart Home Automation System 🏠⚡

An ESP8266-powered smart home automation and security system designed for intelligent appliance control, environmental monitoring, and real-time security management through a cyber-themed web dashboard. The project integrates IoT communication, embedded systems, and automation technologies to create a centralized smart home ecosystem.

---

# ✨ Features

- Secure cyber-themed web dashboard
- Real-time temperature and device monitoring
- Ultrasonic and PIR-based intrusion detection
- Servo motor controlled smart door lock system
- PWM-based intelligent fan speed regulation
- Real-time alert system using buzzer notifications
- Interactive appliance control interface
- Dynamic environmental monitoring and automation

---

# 🧠 System Overview

The system uses an ESP8266 NodeMCU as the central controller to monitor sensor inputs and automate home devices. Environmental conditions and security events are continuously processed and displayed through a responsive web dashboard interface.

The project combines embedded hardware components with web-based control mechanisms to provide a smart, efficient, and secure automation platform.

---

# 🔧 Hardware Components

| Component | Purpose |
|---|---|
| ESP8266 NodeMCU | Main controller and WiFi communication |
| HC-SR04 Ultrasonic Sensor | Intrusion detection |
| PIR Motion Sensor | Motion sensing |
| LM35 Temperature Sensor | Temperature monitoring |
| MG90S Servo Motor | Smart door locking |
| DC Fan | Automated airflow control |
| LCD 16x2 Display | Status monitoring |
| Buzzer | Security alerts |
| LEDs | Lighting indication and control |

---

# 📍 GPIO Pin Mapping

| Component | Pin | Function |
|---|---|---|
| Light / LED | D0 | Lighting Control |
| LM35 Sensor | A0 | Temperature Input |
| Buzzer | D4 | Alert System |
| Ultrasonic Sensor | D5 / D6 | Distance Detection |
| Fan Control | D7 | PWM Fan Regulation |
| Servo Motor | D8 | Door Lock Mechanism |
| PIR Sensor | D3 | Motion Detection |

---

# 💻 Software Stack

## Technologies Used

- Arduino C++
- HTML5
- CSS3
- JavaScript
- ESP8266 Web Server

## Libraries Used

- ESP8266WiFi.h
- ESP8266WebServer.h
- Servo.h
- LiquidCrystal_I2C.h

---

# ⚙️ Functional Modules

## 🔐 Smart Security

- Motion and intrusion detection using PIR and ultrasonic sensors
- Real-time alert generation using buzzer notifications
- Servo-based automated locking mechanism

## 🌡️ Environmental Monitoring

- Continuous temperature sensing using LM35
- Intelligent fan speed control through PWM

## 💡 Appliance Automation

- Lighting control through web interface
- Real-time device state updates

## 📊 Web Dashboard

- Dynamic cyber-themed interface
- Live monitoring and control
- Real-time environmental data visualization

---

# 🚀 Setup Instructions

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/smart-home-automation.git
