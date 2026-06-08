## Smart WiFi Controlled Camera Robot
📖 Project Overview

The Smart WiFi Controlled Camera Robot is a surveillance and monitoring system that can be controlled remotely using WiFi.

This robot is equipped with an ESP32-CAM, which provides live video streaming. The user can control the robot’s movement and camera direction from a remote location within a certain range using a mobile or web interface.

It is mainly designed for surveillance purposes, allowing users to monitor a specific area without being physically present.

## Key Features
- Live video streaming using ESP32-CAM
- WiFi-based remote control
- Robot movement (forward, backward, left, right)
- Camera rotation using Pan & Tilt servos
- Relay-controlled external device (like cutter / pump)
- Battery-powered system
## How It Works
- The ESP32-CAM connects to a WiFi network
- The user opens a web/mobile interface
- Live video is streamed from the robot
- The user sends commands to control:
 Robot movement-
 Camera rotation-
 External devices (ON/OFF)-
- The ESP32 processes the commands and controls:
  Motor driver (for movement),
  Servo motors (for camera angle),
  Relay module (for external load),
## Applications
- Home Surveillance
- Agriculture Monitoring
- Industrial Inspection
- Security Patrol Robot
## Future Scope
- Mobile App Integration
Develop a dedicated Android/iOS app for better and easier control of the robot.
- Night Vision Capability
Add IR sensors or night vision camera to enable monitoring in low-light or dark conditions.
  - AI-Based Object Detection
Integrate AI/ML models to detect humans, animals, or intruders automatically.
- Extended Control Range (Internet Control)
Upgrade from local WiFi to cloud-based control so the robot can be operated from anywhere in the world.
- GPS Tracking System
Add GPS module to track the real-time location of the robot.
  - Two-Way Audio Communication
Integrate microphone and speaker for real-time voice communication.
- Obstacle Avoidance System
