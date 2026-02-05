# Internet of Things (IoT) Experiments using ESP8266

This repository contains a collection of Internet of Things (IoT) experiments implemented using the ESP8266 (NodeMCU) microcontroller.  
The experiments demonstrate real-time sensor data acquisition and cloud-based monitoring using the ThingSpeak IoT platform.

The repository is created as part of academic and practical learning in IoT.

---

## 🔬 Experiments Included

1. IoT-based Temperature and Humidity Monitoring System  
2. IoT-based Water Level Monitoring System  

Each experiment uses sensors interfaced with the ESP8266 to collect data and upload it to the cloud for visualization and analysis.

---

## 1️⃣ IoT-based Temperature and Humidity Monitoring System

### Description  
This experiment monitors ambient temperature and humidity using a DHT11 sensor connected to an ESP8266 NodeMCU.  
The sensor data is transmitted over WiFi and visualized in real time using the ThingSpeak cloud platform.

### Objective  
To design and implement an IoT system for remote monitoring of temperature and humidity.

### Hardware Components  
- ESP8266 NodeMCU  
- DHT11 Temperature and Humidity Sensor  
- Breadboard and connecting wires  
- WiFi Network  

### Software & Tools  
- Arduino IDE  
- ESP8266WiFi Library  
- DHT Sensor Library  
- ThingSpeak API  

### Working Principle  
The DHT11 sensor measures temperature and humidity and sends the digital data to the ESP8266.  
The ESP8266 connects to a WiFi network and uploads the sensor readings to the ThingSpeak cloud at regular intervals.  
The data is stored and visualized as graphs for real-time monitoring.

### ThingSpeak Fields  
- Field 1: Temperature (°C)  
- Field 2: Humidity (%)  

### Dataset  
- `temperature_humidity_data.csv` – Sample temperature and humidity readings exported from ThingSpeak.

### Applications  
- Weather monitoring systems  
- Smart home automation  
- Environmental monitoring  
- Agricultural monitoring  

---

## 2️⃣ IoT-based Water Level Monitoring System

### Description  
This experiment implements a water level monitoring system using a water sensor interfaced with an ESP8266 NodeMCU.  
The sensor readings are uploaded to the ThingSpeak cloud using a single field.

### Objective  
To monitor water presence or level remotely using an IoT-based solution.

### Hardware Components  
- ESP8266 NodeMCU  
- Water Level Sensor  
- Breadboard and connecting wires  
- WiFi Network  

### Software & Tools  
- Arduino IDE  
- ESP8266WiFi Library  
- ThingSpeak API  

### Working Principle  
The water sensor detects the presence or level of water and produces a corresponding electrical signal.  
The ESP8266 reads this value and transmits it to the ThingSpeak cloud over WiFi at fixed intervals.  
The uploaded data is visualized as a graph on the ThingSpeak dashboard.

### ThingSpeak Fields  
- Field 1: Water Level / Sensor Value  

### Dataset  
- `water_level_data.csv` – Sample water sensor readings exported from ThingSpeak.

### Applications  
- Water tank monitoring  
- Leakage detection  
- Smart irrigation systems  


## 📁 Repository Structure

