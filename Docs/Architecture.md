# AGEV System Architecture

## Overview

AGEV (Autonomous Ground Electric Vehicle) is an ESP32-based autonomous rover designed for obstacle detection and intelligent navigation.

## System Components

### Processing Unit
- ESP32 Development Board

### Sensor Layer
- HC-SR04 Ultrasonic Sensor
- Optional LiDAR Module
- Optional GPS Module

### Control Layer
- L298N Motor Driver

### Actuation Layer
- 4WD DC Motors

### Power System
- Rechargeable Battery Pack

## Operational Workflow

1. Sensor scans environment
2. Distance data processed by ESP32
3. Obstacle detection algorithm executed
4. Motor control decision generated
5. Rover changes direction or proceeds forward

## Future Improvements

- SLAM Integration
- GPS Navigation
- LiDAR Mapping
- Cloud Telemetry
- Mobile Application Control