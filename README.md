# Smart-Grain-Storage-Spoilage-Prevention-System
AI and IoT based Smart Grain Storage System for real time monitoring and spoilage prediction.
## 📌Problem Statement
Grain stored in warehouse can deteriorate due to unfavorable environment conditions such as: 
- High temperature.
- High humidity.
- Excess moisture.
- harmful gases.
- Insect infestation.
- Poor ventilation.
- Long storage duration.
## 💡Proposed solution.
#### IoT + Sensors + ESP32 + Ai/TinyML + Dashboard + Alert System.

### storage grain
     Storage grain --> sensors --> ESP32 --> sensor data processing --> TinyML AI --> Spoilage Risk Analysis
                                                                                           |---> SAFE --> Normal operation
                                                                                           |---> WARNING --> Alert --> IoT Dashboard
                                                                                           |---> CRITICAL --> Immediate Action
---
### System Architecture.
    Temperature sensor-----|
    Humidity Sensor--------|
    Gas Sensor-------------|
    Moisture Sensor--------|
    Insect Detection-------|
    Sack temperature-------|
                           |
                         ESP32
                           |
                    Data Processing
                           |
                      TinyML Model
                           |
                  Spoilage Prediction
                           |
                  _________|_________
                  |                  |
           IoT Dashboard        Local Alerts
                  |                  |
          Real-time Data       Buzzer/LED
## Hardware component
| component | purpose |
| --- | --- |
| ESP32 | Main microcontroller |
| DS18B16 | Measures grain/sack temperature |
| MO-135 | Detects gas levels |
| Moisture Sensor | Measures moisture |
| DHT22 | Measures temperature and humidity |
| OLED display | Displays sensors information |
| Buzzer | Provides warning alerts |
| LED | Shows system status |
#### "the components may vary between the simulation and physical prototype"
---
## AI/TinyML
The system use the lightweight TinyMl model for the intelligent grain spoilage risk prediction.

Sensor values are collected and processed before being supplied to the trained model.

| Indoor temperature |
| --- |
| Indoor humidity |
|  |

