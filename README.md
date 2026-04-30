# Access Control & Room Security System

## Overview
A comprehensive security system designed to manage authorized entry and automate room environments. The project focuses on combining access management with smart energy-saving features.

## Features
* **Controlled Access:** Authentication-based entry (Keypad/RFID) to ensure only authorized personnel enter.
* **Security Monitoring:** Sensors to detect unauthorized entry or environmental hazards.
* **Smart Automation:** Automatically toggles lights and appliances based on occupancy to reduce energy waste.
* **Status Display:** Real-time feedback via LCD/Serial Monitor regarding system status and entry logs.

## Hardware Stack
* **Microcontroller:** Arduino / ESP32
* **Inputs:** RFID Module / 4x4 Keypad / PIR Motion Sensor
* **Outputs:** 16x2 LCD Display / Solenoid Lock / Relay Module
* **Indicators:** Active Buzzers and LEDs for alarm/status signals.

## System Logic
1. System waits for valid credential input.
2. Upon verification, the solenoid lock engages and room loads (lights/fans) activate.
3. PIR sensors monitor occupancy to maintain active status.
4. System logs the entry and resets upon exit or timeout.
