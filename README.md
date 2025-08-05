# 💊 Intelligent Medicine Monitoring & Smart Refill Alert System

<p align="center">
  <img src="medicine-monitoring-banner.png" width="600" alt="Medicine Monitoring System Banner"/>
</p>

---

## 📖 Project Overview

The **Intelligent Medicine Monitoring & Smart Refill Alert System** is an **IoT-based healthcare project** that ensures patients **never miss their medications**.  
It **monitors medicine intake**, **sends reminders**, and **triggers smart refill alerts** when medicine stock is low.  

This project is designed to **support elderly patients, hospitals, and busy individuals** by **reducing missed doses and medication errors**.

---

## ⚡ Features

- ✅ **Medicine Intake Reminders** via buzzer/notifications  
- ✅ **Smart Refill Alerts** when the medicine container is low  
- ✅ **Real-time Monitoring** using IoT and sensors  
- ✅ **Cost-effective, scalable healthcare solution**  
- ✅ **Can be integrated with cloud dashboards for remote monitoring**  

---

## 🛠️ Hardware Components

| Component                | Description                             |
|--------------------------|-----------------------------------------|
| ESP32 / Arduino Nano     | Microcontroller for IoT and Wi-Fi        |
| IR Sensors               | Detect medicine intake or container status |
| Load Cell / Weight Sensor| Detect remaining medicine quantity       |
| Buzzer / LED             | Alerts & reminders                       |
| LCD Display              | Shows status and notifications           |

---

## 🧰 Software & Libraries

- **Arduino IDE / PlatformIO** (Programming)  
- **C / C++ for microcontrollers**  
- **IoT Libraries:**  
  - `WiFi.h` (ESP32 Wi-Fi)  
  - `Blynk` or `MQTT` (for cloud alerts)  
  - `HX711.h` (for weight sensor data)  

---

## ⚙️ Working Principle

1. **Monitoring Phase:**  
   - IR and weight sensors **track medicine intake** and **remaining stock**.  

2. **Alert Phase:**  
   - **Buzzer or LED** triggers if a scheduled dose is missed.  
   - **Smart Refill Alert** is sent when medicine is low.  

3. **Cloud Connectivity (Optional):**  
   - ESP32 sends data to a **mobile app or cloud dashboard** for **remote monitoring**.

<p align="center">
  <img src="system-architecture.png" width="600" alt="System Architecture Diagram"/>
</p>

---

## 📂 Project Structure

