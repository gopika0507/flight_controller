# 🚁 Drone Flight Controller – Embedded Systems Project

This project focuses on the design and development of a **custom drone flight controller** using embedded systems and sensor integration. The controller is responsible for stabilizing, navigating, and controlling a quadcopter using real-time sensor data and control algorithms.

---

## 📌 Project Objectives
- Design a low-cost and efficient flight controller for a quadcopter.
- Interface IMU sensors with a microcontroller.
- Implement PID control for stable flight.
- Control BLDC motors using ESCs.
- Enable manual and autonomous flight control.
- Support real-time telemetry and debugging.

---

## ⚙️ Hardware Components Used
- Microcontroller (ESP32 / STM32 / Arduino / ATmega – specify yours)
- IMU Sensor (MPU6050 / MPU9250)
- BLDC Motors
- Electronic Speed Controllers (ESCs)
- Li-Po Battery
- RF Transmitter & Receiver / Bluetooth / Wi-Fi
- Power Distribution Board (PDB)
- Drone Frame

---

## 💻 Software & Tools
- Embedded C / Arduino IDE / PlatformIO
- PID Control Algorithms
- I2C Communication Protocol
- Serial Communication for Debugging


---

## 🔁 System Working (High-Level Flow)

1. IMU sensor reads acceleration and gyroscope data.
2. Sensor data is filtered and processed.
3. PID controller calculates correction values.
4. PWM signals are generated for ESCs.
5. ESCs drive the BLDC motors.
6. Drone stabilizes and executes flight commands.

---


