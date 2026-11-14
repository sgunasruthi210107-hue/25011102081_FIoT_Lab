PROJECT
# CAT15 – Smart Rice Crop Irrigation System Using BME Sensor

## Project Overview
The Smart Rice Crop Irrigation System is an IoT-based agricultural application designed to automate irrigation for rice cultivation using a BME sensor.

The system monitors environmental conditions using the BME sensor and automatically controls irrigation based on the sensed values, reducing manual intervention and improving irrigation management.

## Aim
To develop a smart irrigation system for rice crops using a BME sensor, where irrigation is automatically controlled according to sensor readings.

## Problem Statement
Traditional irrigation systems require manual monitoring and control, which can lead to inefficient water usage and unnecessary irrigation.

This project aims to automate irrigation for rice crops by monitoring sensor data and controlling the irrigation system accordingly.

## Hardware Components
- BME Sensor
- Microcontroller / Development Board
- Irrigation Pump or Water Control Mechanism
- Connecting Wires
- Power Supply

## Working Principle
1. The BME sensor measures environmental parameters.
2. The sensor values are read by the microcontroller.
3. The measured values are analyzed based on predefined irrigation conditions.
4. The irrigation system is automatically switched ON or OFF according to the sensor readings.
5. The process continues periodically to maintain the required irrigation conditions.

## System Architecture

```text
BME Sensor
    |
    v
Microcontroller
    |
    v
Sensor Value Processing
    |
    v
Irrigation Decision
    |
    v
Pump / Irrigation Control
```

## Features
- Sensor-based irrigation control.
- Automatic irrigation switching.
- Real-time environmental monitoring.
- Reduced manual intervention.
- Improved irrigation management for rice cultivation.

## Node-RED Implementation

### Node-RED Flow 1
![Node Red 1](Node%20red%201.jpeg)

### Node-RED Flow 2
![Node Red 2](Node%20Red%202.jpeg)

## Result
A sensor-based smart irrigation system for rice cultivation is developed, where irrigation automatically changes according to the BME sensor readings.
