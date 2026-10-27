# Smart-V2V-Safety-Broadcast-System
Low-cost vehicle-to-vehicle communication system for accident prevention

Project Overview

Smart V2V Safety Broadcast System is a low-cost vehicle-to-vehicle communication system designed to improve road safety by sharing alerts between nearby vehicles.

Problem Statement

Sudden braking, blind-spot hazards, and delayed warnings can lead to preventable road accidents. Many advanced safety systems are expensive or depend on GPS and cellular connectivity.

Proposed Solution

Our system uses Arduino, nRF24L01 RF modules, and an MPU6050 accelerometer to detect sudden braking and broadcast alerts directly to nearby vehicles without requiring GPS or cellular networks.

Key Features

- Sudden Braking Alert: Detects sudden deceleration and warns nearby vehicles.
- Blind-Spot Warning: Simulates detection of nearby vehicles during lane changes.
- Multi-Hop Alert Relay: Relays braking warnings through intermediate vehicles to reach vehicles farther away.

Technologies Used

- Python — software simulation
- Arduino — planned hardware controller
- nRF24L01 — planned wireless communication
- MPU6050 — planned acceleration sensing

Project Modules

1. Module I — Core Braking Alert
2. Module II — Blind-Spot Warning
3. Module III — Multi-Hop Chain-Braking Relay

Current Development Stage

The three modules have software simulation code. Physical hardware assembly and real-world testing are still in progress.

Expected Impact

The project aims to make vehicle safety alerts more affordable and accessible, particularly for budget vehicles and two-wheelers.

Disclaimer

This project is a prototype under development. The software simulations do not establish real-world detection accuracy or accident-prevention performance.
