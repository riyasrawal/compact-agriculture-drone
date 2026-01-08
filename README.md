# Compact Agriculture Drone

**Capstone Project - EE300W**

## Project Overview

A lightweight, 3D-printed FPV drone designed for agricultural site management and crop health monitoring. This project addresses the inefficiency of manual field inspection by providing an affordable, user-friendly aerial monitoring solution.

### Problem Statement
Traditional agricultural inspection is:
- **Time-consuming** - Manual field walks are labor-intensive
- **Inefficient** - Limited coverage and delayed problem detection
- **Non-affordable** - Commercial agricultural drones are expensive

### Purpose
- **Detect Crop Health** - Early identification of issues
- **Optimize Resources** - Better irrigation and fertilizer management  
- **Improve Productivity** - Data-driven decision making

## Key Features
- **Lightweight Design** - 3D-printed frame for easy portability
- **FPV Camera** - Real-time video streaming for monitoring
- **Wireless Control** - Manual operation via RF transceiver
- **Arduino-Based** - Arduino Pro Mini flight controller
- **Gyroscope Stabilization** - MPU6050 sensor for stable flight
- **Quick Assembly** - Designed for easy setup and disassembly

## System Architecture

### Drone Subsystem (DD & RR)
- **Frame**: 3D-printed lightweight structure
- **Flight Controller**: Arduino Pro Mini (3.3V)
- **Sensors**: MPU6050 Gyroscope for acceleration and speed control
- **Motors**: 4x Coreless Motors (6mm) with propellers
- **Communication**: NRF24L01 RF Transceiver
- **Camera**: FPV Camera for real-time monitoring
- **Battery**: 3.7V 220mAh LiPo
- **Additional**: 5V Buzzer, SMD components (MOSFETs, resistors, diodes)

### Controller Subsystem (DA & AH)
- **Microcontroller**: Arduino Nano
- **Display**: 16x2 LCD for status information
- **Input**: Joystick Module for flight control
- **Communication**: RF Transceiver with long antenna
- **Interface**: Rotary encoder for menu navigation
- **Battery**: 7.4V dual battery pack
- **Controls**: Toggle switches, potentiometers, power switches

## Technical Specifications

### Components
**Total Budget**: $250.33
- Drone Components: $192.65
- Controller Components: $57.68

### Key Electronic Components
- **Arduino Pro Mini** (3.3V) - Flight controller
- **MPU6050 Sensor** - Gyroscope and accelerometer
- **NRF24L01 Transceiver** - Wireless communication
- **SMD MOSFET (SI2300)** - Motor control
- **Schottky Diodes (SS14)** - Protection circuits
- **FPV Camera** (26.99) - Live video feed

## My Contributions

As part of the **Mechanical Team**, I focused on:
- 3D-printed drone frame design and prototyping
- Part acquisition and budget management
- Research on agricultural drone applications
- Component assembly and integration
- Project documentation and presentation materials

## Project Timeline

**Completed:**
- ✅ Project planning and Gantt chart creation
- ✅ System block diagram development
- ✅ Abstract and proposal documentation
- ✅ Parts acquisition (drone and controller)
- ✅ Research on agricultural applications

**Current Status:**
- 🔧 3D printing drone body and controller enclosure
- 🔧 Circuit assembly and component integration
- 🔧 Transmitter coding

**Upcoming:**
- Testing and debugging
- Final system integration
- Field testing and demonstrations

## Use Cases

### Agricultural Applications
1. **Site Surveying** - Aerial mapping and 3D modeling
2. **Progress Monitoring** - Track crop growth over time
3. **Safety Inspection** - Access hard-to-reach areas
4. **Material Tracking** - Monitor equipment and supplies
5. **Quality Control** - Early detection of crop issues

## Team

**Mechanical Team**: Dylan Dress, Riya Rawal  
**Electrical Team**: Dina Azlan, Alex Huang  

**Instructor**: EE300W Capstone Course

## Project Status

**Expected Completion**: Spring 2025

**Goals:**
- Functional and efficient drone for agricultural applications
- User-friendly controller with intuitive interface
- Reliable wireless communication and stable flight
- Complete documentation and demonstration

---

*Developed as part of Penn State's EE300W Capstone Project*
