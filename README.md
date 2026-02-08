# 🌊 Real-Time River Water Quality Monitoring System

An **IoT and cloud-based solution** for monitoring river water quality parameters in real time.  
The system collects sensor data, sends it to the cloud, visualizes it on dashboards, and triggers SMS alerts when unsafe conditions are detected.

---

## 📌 Problem Statement

Traditional water quality testing is manual, time-consuming, and does not provide real-time insights.  
This project automates water quality monitoring using IoT devices and cloud services to enable continuous and remote observation.

---

## 🧠 System Architecture

Sensors → ESP8266 → IBM Watson IoT → Node-RED → Dashboard → SMS Alerts


---

## ⚙️ Features

- Real-time water quality data collection  
- Cloud-based data ingestion and processing  
- Live dashboards for visualization  
- Threshold-based SMS alert system  
- Scalable and modular IoT architecture  

---

## 🛠️ Tech Stack

### Hardware
- ESP8266 / Microcontroller  
- pH Sensor  
- Turbidity Sensor  
- Temperature Sensor  

### Software & Cloud
- Python  
- IBM Watson IoT Platform  
- Node-RED  
- MQTT Protocol  
- Fast2SMS API  

---

## 📊 Dashboard

Displays real-time graphs for:
- Temperature
- pH
- Turbidity
  
Implemented using Node-RED Dashboard.

Auto-updates from cloud data streams.
