# IoT-based Temperature and Humidity Monitoring System

This project demonstrates an Internet of Things (IoT) based system for monitoring temperature and humidity using an ESP8266 NodeMCU and a DHT11 sensor.  
The sensed environmental data is transmitted over WiFi and visualized in real time using the ThingSpeak cloud platform.

---

## 📌 Objective

To design and implement a cloud-connected system that measures temperature and humidity and enables remote monitoring using an IoT platform.

---

## 🔧 Hardware Components Used

- ESP8266 NodeMCU
- DHT11 Temperature and Humidity Sensor
- Connecting Wires
- Breadboard
- WiFi Network

---

## 🧪 Software & Tools Used

- Arduino IDE
- ESP8266WiFi Library
- DHT Sensor Library
- ThingSpeak API
- ThingSpeak Cloud Platform

---

## ⚙️ Working Principle

The DHT11 sensor measures the ambient temperature and humidity and sends the digital data to the ESP8266 NodeMCU.  
The ESP8266 connects to a WiFi network and uploads the sensor readings to the ThingSpeak cloud at regular intervals.

The uploaded data is stored and visualized in the form of graphs, enabling real-time remote monitoring of environmental conditions.

---

## ☁️ Cloud Integration

- Platform Used: **ThingSpeak**
- Field 1: Temperature (°C)
- Field 2: Humidity (%)
- Data is updated periodically based on the delay configured in the program.

---

## 📊 Dataset

Sample sensor readings collected during the experiment have been exported from ThingSpeak and stored as a CSV file for reference and analysis.

- `temperature_humidity_data.csv` – Sample temperature and humidity readings

---

## ✨ Features

- Real-time temperature monitoring
- Real-time humidity monitoring
- Cloud-based data storage and visualization
- Remote access to sensor data

---

## 📌 Applications

- Weather monitoring systems
- Smart homes
- Environmental monitoring
- Agricultural monitoring

---

## 👩‍💻 Author

**Meenal Priyadharshini**  
IoT Experiments using ESP8266 and ThingSpeak
