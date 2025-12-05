# 55-T-TRAIL

**Smart Multi-Train Magnetic System with Virtual Block Scheduling**  
*Following the path of innovation and legacy — a tribute to David Kamau*

---

## Overview

**55-T-TRAIL** is a **smart, magnetically guided model train system** designed to simulate **autonomous multi-train operations**. The system ensures:

- Collision-free scheduling
- On-time arrivals
- Dynamic block management
- Smooth acceleration and braking

The prototype integrates **Arduino for motor and sensor control**, **Python for real-time scheduling and ETA calculation**, and **Rust for backend logic and safety-critical algorithms**.  

This project is a **tribute to David Kamau**, symbolizing legacy, innovation, and continuous movement forward.

---

## Features

- **Multi-Train Control**: Manage several trains on the same track without collisions  
- **Virtual Block Management**: Dynamically generated “infinite” blocks for precise scheduling  
- **Magnetic Guidance**: Train alignment and propulsion using magnetic sensors  
- **Smooth Acceleration/Deceleration**: Triangular motion profile for realistic movement  
- **Real-Time Monitoring**: Front and rear train positions tracked for block reservation  
- **Cross-Platform Control**: Arduino + Python + Rust integration  

---

## Tech Stack

- **Arduino**: Motor control, sensor input (Hall sensors, reed switches)  
- **Python**: Scheduling algorithms, ETA calculations, block management  
- **Rust**: Backend logic, safety-critical operations, multi-train coordination  
- **Optional**: UI/Frontend for simulation or mobile app integration  

---

## Block Management

- Each track is divided into **logical blocks** (virtual or physical)  
- **Train length is considered** — blocks are only free when the **entire train leaves**  
- **Scheduler** reserves upcoming blocks to prevent collisions  
- Supports **dynamic tracks and loops**, simulating “infinite” blocks  

---

## Getting Started

### Requirements

- Arduino board (Uno, Mega, or similar)  
- Hall effect sensors or reed switches  
- Magnetic model train  
- Python 3.10+  
- Rust 1.70+  

### Setup

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/55-T-TRAIL.git
