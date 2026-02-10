# Ultrasonic Radar System using Arduino & Processing

A real-time **radar visualization system** built using an **Arduino UNO**, **HC-SR04 ultrasonic sensor**, **servo motor**, and **Processing IDE**.  
The servo sweeps the ultrasonic sensor across angles while distance data is visualized as a radar screen on the computer.

---

## 📌 Features
- Real-time radar sweep (0°–180°)
- Distance detection using ultrasonic sensor
- Live visualization using Processing
- Simple serial communication
- Beginner-friendly & interview-ready project

---

## 🧰 Hardware Requirements
- Arduino UNO
- Ultrasonic Sensor (HC-SR04)
- Servo Motor (SG90 / MG90)
- Jumper wires
- External 5V supply (recommended for servo)
- USB cable

---

## 🔌 Circuit Connections

### Ultrasonic Sensor (HC-SR04)
| Sensor Pin | Arduino Pin |
|----------|-------------|
| VCC | 5V |
| GND | GND |
| TRIG | D9 |
| ECHO | D10 |

### Servo Motor
| Servo Pin | Arduino Pin |
|---------|-------------|
| Signal | D6 |
| VCC | 5V (external recommended) |
| GND | GND |

> ⚠️ Use a **common ground** if external power is used for the servo.

---

## 💻 Software Requirements
- **Arduino IDE**
- **Processing IDE**
- USB Serial Driver (if required)

---

## 📂 Code Overview

### Arduino (`Arduino_Code/ultrasonic_radar.ino`)
- Controls servo sweep
- Triggers ultrasonic sensor
- Measures distance
- Sends angle & distance via serial

**Serial format:**
