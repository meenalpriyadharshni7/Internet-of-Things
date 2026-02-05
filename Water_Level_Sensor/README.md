---

### 2️⃣ IoT-based Water Level Monitoring System

**Description:**  
This experiment implements a water level monitoring system using a water sensor interfaced with an ESP8266 NodeMCU.  
The sensor output is read by the microcontroller and uploaded to the ThingSpeak cloud platform using a single field.

**Working Principle:**  
The water sensor detects the presence or level of water and produces a corresponding electrical signal.  
The ESP8266 reads this value and transmits it to ThingSpeak over WiFi at regular intervals, where the data is visualized as a graph.

**Components Used:**
- ESP8266 NodeMCU
- Water Level Sensor
- WiFi Network
- ThingSpeak Cloud Platform

**Features:**
- Real-time water level monitoring
- Cloud-based data logging using ThingSpeak
- Single-field data update
- Suitable for tank monitoring and leakage detection

**Dataset:**
- `water_level_data.csv` – Sample water sensor readings exported from ThingSpeak
