# Intrusion-Detection-System-Using-PIR-Sensor

## 📘 Project Overview
This project demonstrates a simple motion detection and alarm system using an Arduino Uno and a PIR (Passive Infrared) sensor. When motion is detected, the system activates a buzzer and an LED to alert the user. It serves as a basic example of how microcontrollers can be used in security and surveillance applications.

---

## 🧰 Components Used

| Component         | Quantity | Description                                 |
|-------------------|----------|---------------------------------------------|
| Arduino Uno       | 1        | Main microcontroller board                  |
| PIR Sensor        | 1        | Digital motion detection sensor             |
| Buzzer            | 1        | Audio alert device                          |
| LED               | 1        | Visual alert indicator (optional)           |
| 220Ω Resistor     | 1        | Protects the LED from high current          |
| Jumper Wires      | As needed | For connecting components                   |
| Breadboard        | 1        | For organizing the circuit                  |

---

## 🔌 Circuit Connections

### PIR Sensor:
- **VCC** → Arduino 5V
- **GND** → Arduino GND
- **OUT** → Digital Pin D2

### Buzzer:
- Positive terminal → Digital Pin D8  
- Negative terminal → GND

### LED (Optional):
- Positive terminal → 220Ω resistor → Digital Pin D13  
- Negative terminal → GND

---

## ⚙️ How It Works

1. Once powered on, the Arduino continuously monitors the PIR sensor.
2. If motion is detected (`OUT = HIGH`):
   - The buzzer is activated.
   - The LED turns on.
   - A message is printed to the Serial Monitor: `"🚨 Motion detected!"`
3. If no motion is detected, the buzzer and LED are turned off.

---
🎨 Designed by Aryam
