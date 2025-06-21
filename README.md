# Empowering-Disaster-Response-with-IoT-Hardware
A Core Subsystem in a Secure, Decentralized Early Warning Architecture

---

# 📡 IoT & Hardware System for a Secure Early Warning System

This repository contains the IoT and Hardware implementation of a **Secure, Decentralized Early Warning System for Disasters and Crises**.  
The system is part of a multidisciplinary graduation project integrating AI, Backend, Frontend, Mobile, and Smart Contracts.

---

## 🚀 Overview

The IoT subsystem is responsible for detecting early signs of environmental hazards using sensors for:
- Toxic gases (MQ2)
- Carbon Monoxide (MQ7)
- Temperature & Humidity (DHT11)
- Fire/Flame (IR sensor)

The collected data is processed via an **ESP32** microcontroller and:
- Streamed to **Blynk IoT dashboards**
- Forwarded to backend services and an AI model for further validation
- Sent as alerts via **Wi-Fi & SMS**

---

## 🔧 Hardware Components

| Component        | Specification           | Purpose                    |
|------------------|--------------------------|-----------------------------|
| ESP32            | Wi-Fi-enabled MCU        | Main controller             |
| MQ2 Sensor       | Analog (LPG, Smoke)      | Detect flammable gases      |
| MQ7 Sensor       | Analog (CO)              | Detect Carbon Monoxide      |
| DHT11 Sensor     | Digital                  | Measure temperature/humidity|
| IR Flame Sensor  | Digital (HIGH on flame)  | Fire detection              |
| LED              | 5mm Red                  | Visual Alarm                |

---

## 📷 Wiring Diagram

![Wiring Diagram](https://github.com/Reemnazeeh/Empowering-Disaster-Response-with-IoT-Hardware/blob/main/images/IMG-20241207-WA0109.jpg)

---

## 💡 Features

- ✅ Real-time sensor data acquisition
- ✅ Low false alarms via AI validation
- ✅ Blynk Web & Mobile dashboards
- ✅ Multiple alert channels: Wi-Fi, SMS
- ✅ Scalable IoT design

---

## 🖥️ Blynk Dashboard

![Blynk Dashboard](https://github.com/Reemnazeeh/Empowering-Disaster-Response-with-IoT-Hardware/blob/main/images/IMG-20250510-WA0142.jpg)

---

## 🔌 Hardware Testing

![Hardware Testing](https://github.com/Reemnazeeh/Empowering-Disaster-Response-with-IoT-Hardware/blob/main/images/IMG-20250510-WA0129.jpg)

---

## 📥 Download Documentation

📄 [Download IoT & Hardware Final PDF](https://github.com/Reemnazeeh/Empowering-Disaster-Response-with-IoT-Hardware/blob/main/Air%20Quality%20%26%20Fire%20Monitoring%20System.pdf)

---

## 🏆 Project Achievements

This system was awarded **First Place** in the qualifying round of the **Summit Forum for Scientific and Engineering Innovations**  
at the level of the Ministry of Higher Education Institutes (Egypt).

---

## 📬 Contact

**Reem Nazeh**  
IoT & Hardware Track Lead  
📧 reem1nazeh@gmail.com  
🔗 [GitHub: Reemnazeeh](https://github.com/Reemnazeeh)  
🔗 [LinkedIn: Reem Nazeh](https://www.linkedin.com/in/reem-nazeh-9a8690229?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

---

## 📌 Final Note

This subsystem plays a crucial role in the overall system architecture, enabling real-time monitoring and smart responses to potential environmental crises.

For full system design and code, visit the [main project repository](https://github.com/Reemnazeeh/Empowering-Disaster-Response-with-IoT-Hardware/blob/main/Air%20Quality%20%26%20Fire%20Monitoring%20System.pdf).
