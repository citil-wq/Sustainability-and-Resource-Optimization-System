# Sustainability and Resource Optimization System

## Overview
The Sustainability and Resource Optimization System is a full-stack IoT-based application designed to optimize resource utilization within institutional environments. It integrates smart infrastructure booking, energy automation, and real-time monitoring of electricity and water consumption into a unified platform.

---

## Features
- Google OAuth-based authentication  
- Role-based access (Admin / Faculty)  
- Smart lab booking system with real-time availability  
- IoT-based energy automation (lights and fans control)  
- Real-time dashboards for electricity and water monitoring  
- Alert system for abnormal resource usage  

---

## Tech Stack

### Frontend
- React.js  
- HTML  
- CSS  
- JavaScript  

### Backend
- Node.js  
- Express.js  

### Database
- MongoDB Atlas  
- InfluxDB (for time-series IoT data)  

### IoT and Hardware
- ESP32 Microcontroller  
- Sensors:
  - DHT11 (Temperature and Humidity)  
  - PIR (Motion Detection)  
  - LDR (Light Intensity)  
  - Ultrasonic Sensor (Water Level Monitoring)  

### Visualization
- Grafana  

### Authentication
- Google OAuth  

---

## System Architecture

Sensors
  ↓
ESP32
  ↓
Backend (Node.js)
  ├── MongoDB (application data)
  ├── InfluxDB (sensor data) → Grafana (dashboard)
  └── Frontend (React)


---

## Modules

### 1. Smart Lab Booking System
- Real-time slot availability  
- Admin approval workflow  
- Booking history and notifications  

### 2. Energy Automation System
- Motion-based control using PIR sensor  
- Light-based automation using LDR sensor  
- Temperature-based adjustments using DHT11 sensor  

### 3. Electricity and Water Monitoring
- Real-time tracking of resource usage  
- Threshold-based alert system  
- Visualization through Grafana dashboards  

---

## Key Contributions
- Developed the full-stack application (frontend and backend)  
- Implemented authentication and role-based routing  
- Integrated IoT dashboards into a unified platform  
- Designed system architecture and coordinated development  

---

## Limitations
- Prototype-level implementation  
- Limited scalability  
- No cloud deployment  

---

## Future Enhancements
- Cloud deployment (AWS / Azure)  
- Advanced analytics and machine learning-based optimization  
- Mobile application integration  
- Expansion to waste management modules  

---
