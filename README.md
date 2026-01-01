# ESP32 7-in-1 Soil Health Monitoring System (RS485 + MQTT)

A smart IoT-based soil monitoring system using **ESP32**, **RS485 Modbus RTU**, and **MQTT** to measure real-time soil health parameters including **Nitrogen (N), Phosphorus (P), Potassium (K), pH, Electrical Conductivity (EC), Soil Temperature, and Soil Moisture**.

This project is designed as a **modular, reusable, and scalable prototype** for smart agriculture and greenhouse automation.

---

##  Features

-  RS485 Modbus RTU communication
-  Measures **7 soil parameters** using a single sensor
-  ESP32 Wi-Fi connectivity
-  MQTT data publishing
-  JSON formatted payload
-  Clean and reusable firmware
-  Cloud & dashboard ready (Node-RED, ThingsBoard, AWS IoT, etc.)

---

##  Parameters Measured

| Parameter | Unit |
|---------|------|
| Nitrogen (N) | mg/kg |
| Phosphorus (P) | mg/kg |
| Potassium (K) | mg/kg |
| pH | pH |
| Electrical Conductivity (EC) | µS/cm |
| Soil Temperature | °C |
| Soil Moisture | % |

---

##  Hardware Used

- ESP32 Development Board  
- 7-in-1 Soil Sensor (RS485 Modbus RTU)  
- RS485 to TTL Converter (MAX485)  
- Power Supply (5V / 12V depending on sensor)  
- Connecting Wires  
- Optional Outdoor Enclosure  

---

##  Pin Configuration (ESP32)

| Function | ESP32 Pin |
|--------|-----------|
| RS485 RO (RX) | GPIO 32 |
| RS485 DI (TX) | GPIO 33 |
| RS485 DE/RE | GPIO 25 |
| Baud Rate | 9600 |

---

##  Communication Protocol

- **Sensor Protocol:** Modbus RTU
- **Physical Layer:** RS485
- **Network Protocol:** Wi-Fi
- **IoT Protocol:** MQTT
- **Payload Format:** JSON

---

