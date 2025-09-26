# 🔥 IoT-Based Smoke & Fire Detection System

A smart fire safety solution integrating wireless sensors, edge computing, and cloud services for real-time monitoring, automated threat detection, and emergency response.

---

## 📖 Overview

* **Smoke Detector**: Threshold **0.5 ppm** — placed in bedrooms, living room.
* **CO Detector**: Threshold **0.5 ppm** — placed in living rooms.
* **Fire Monitor**: Installed in kitchens.
* **Fire Sprinkler**: Activates automatically when fire is detected.
* **Automatic Window**: Opens when smoke or CO exceeds **1.5 ppm** and closes when below **0.5 ppm**.

---

## 🏗️ Architecture

* **Edge Layer**: Sensors + Actuators
* **Gateway Layer**: Data collection + forwarding

---

## 📡 Communication Flow

1. Sensors publish data
2. Gateway forwards to server
3. Server processes data and triggers actuators

---

## 🖼️ Visuals

🔹 Device Placement
<img width="771" height="391" alt="image" src="https://github.com/user-attachments/assets/7583987a-54c8-436b-9702-84127917bc37" />

🔹 Fire Detection
<img width="157" height="164" alt="image" src="https://github.com/user-attachments/assets/226d40fc-07e5-46ca-a1c3-1df32a86d107" />

🔹Smoke and CO2 in living room
<img width="387" height="191" alt="image" src="https://github.com/user-attachments/assets/20d9c1b4-fb2c-4a3e-9beb-2b5c9d72e71b" />

🔹Smoke in Bedroom
<img width="354" height="136" alt="image" src="https://github.com/user-attachments/assets/404bc907-2fc7-404e-9aea-0fa14bea4886" />

🔹MCU code
<img width="610" height="319" alt="image" src="https://github.com/user-attachments/assets/a4b2f89f-99f6-4751-a9b0-08809ea5d3c5" />

---

## ⚙️ Technologies

* **Cisco Packet Tracer** – IoT simulation
* **Cloud Integration** – Monitoring + Alerts

---

## 🚀 How It Works

1. Sensors detect smoke, CO, or fire
2. Data sent via **MQTT** to server
3. Server triggers actuators
4. System responds automatically
5. Alerts sent to dashboard and email

---

## ✅ Conclusion

A scalable, real-time IoT system for fire safety — combining smart sensors, MQTT communication, and automated emergency response to protect indoor environments.
