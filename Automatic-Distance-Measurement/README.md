# Automatic Distance Measurement using Arduino

An **ECE project** that uses an **HC-SR04 ultrasonic sensor** with Arduino to measure the distance of objects automatically.  
A **buzzer alert** is triggered when an object comes closer than 15 cm.

---

## 📌 Features
- Uses **ultrasonic sensor (HC-SR04)** for distance measurement.  
- Displays distance readings in **Serial Monitor**.  
- **Buzzer alert** when an object is too close.  
- Simple and cost-effective system for **automation & IoT**.  

---

## 🛠️ Components Required
- Arduino UNO/Nano  
- HC-SR04 Ultrasonic Sensor  
- Buzzer  
- Jumper Wires  
- Breadboard  

---

## ⚡ Circuit Connections
| Ultrasonic Sensor | Arduino Pin |
|-------------------|-------------|
| VCC               | 5V          |
| GND               | GND         |
| TRIG              | D9          |
| ECHO              | D10         |

| Buzzer | Arduino Pin |
|--------|-------------|
| +      | D7          |
| -      | GND         |

---

## 🚀 Getting Started
1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/Automatic-Distance-Measurement.git
   ```
2. Open `src/distance_measurement.ino` in Arduino IDE.  
3. Select your Arduino board & COM port.  
4. Upload the code.  
5. Open **Serial Monitor** (9600 baud) to view distance readings.  

---

## 📷 Demo (Optional)
*(Add images or video of your project here once built)*

---

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
