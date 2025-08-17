# IoT-Based Home Automation System & Auto Water Pump Control

**Team Name:** Team Alpha  
**Supervisor:** Md. Hasibur Rahman, Lecturer  
Department of Computer Science & Engineering  
Khwaja Yunus Ali University  

---

## 📖 Overview
This project focuses on building a **smart IoT-based home automation system** with an **automatic water pump controller** using the **ESP32 NodeMCU**.  

The system enables:
- Remote and manual control of home appliances (2 bulbs, 1 fan, 1 water pump).  
- Automatic water pump control using a **ultrasonic sonar sensor** to measure water level.  
- Environmental monitoring with **DHT11 (temperature & humidity)** and **rain sensor** for weather conditions.  
- Both **auto** and **manual** modes using physical switches or your mobail application.  
- Real-time updates through IoT dashboard (mobile/web).  

This provides a **low-cost, efficient, and user-friendly** smart home solution.  

---

## ⚡ Features
- ✅ Control 2 bulbs, 1 fan, and 1 water pump via IoT or manual switches  
- ✅ Automatic water pump ON/OFF based on tank water level  
- ✅ Rain sensor input to manage pump safety during rainfall  
- ✅ Temperature & humidity monitoring with DHT11  
- ✅ Manual override with 4 physical switches or your mobail app 
- ✅ Real-time IoT monitoring using ESP32 Wi-Fi  

---

## 🛠 Hardware Components
- **ESP32 NodeMCU** (main controller)  
- **Sonar/Ultrasonic Sensor (HC-SR04)** → water tank level measurement  
- **Rain Sensor Module** → detect rain conditions  
- **DHT11 Sensor** → temperature & humidity monitoring  
- **4-Channel Relay Module** → control 2 bulbs, 1 fan, and 1 water pump  
- **4 Manual Switches** → physical override for each device
- **Mobail Appication** → voice command override for each device 
- **Bulbs (x2), Fan (x1), Water Pump (x1)**  
- **Breadboard & Jumper Wires** → prototyping connections  
- **Resistors (330Ω)** → protection for LEDs/sensors  
- **Power Supply** → 5V regulated supply
- **Cork Sheet** → prototype home

---

## 💻 Software Requirements
- Arduino IDE (with ESP32 Board Manager installed)  
- ESP32 Wi-Fi libraries (WiFi.h, AsyncWebServer, etc.)  
- GitHub for version control  
- Optional: Flutter/Android Studio (mobile app), Web framework (dashboard)  

---

## 📂 Repository Structure
/docs → Reports, diagrams, documentation
/hardware → Circuit diagrams, wiring setup, images
/code → ESP32 Arduino/PlatformIO code
/mobile-app → Mobile application (optional)
/web-dashboard → Web control dashboard (optional)
/presentation → Project slides for university
