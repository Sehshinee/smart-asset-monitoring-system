# Smart Asset Monitoring System

## Project Overview

This project proposes a Smart Asset Monitoring System using IoT technology to monitor industrial assets in real time.

The system uses an ESP32 as the main controller and integrates temperature, vibration, and RFID-based asset identification. Monitoring information is intended to be displayed through a web dashboard.

## Objectives

- Monitor asset temperature and vibration in real time.
- Display monitoring data through a web dashboard.
- Identify the current asset location using RFID.
- Provide early warning alerts for abnormal conditions.
- Improve maintenance efficiency through early fault detection.

## Technologies and Components

- ESP32
- DHT11 Temperature Sensor
- SW-420 Vibration Sensor
- RC522 RFID Reader
- RFID Tags
- OLED Display
- Wi-Fi
- Web Dashboard
- Buzzer

## System Operation

The sensors collect temperature and vibration information while the RFID reader identifies the asset.

The ESP32 processes the sensor information and sends the data through Wi-Fi to a web dashboard. The dashboard is intended to display the asset ID, temperature, vibration, location, and alert status.

The system also checks for abnormal conditions and activates an alert when required.

## Project Scope

The system is designed for indoor asset monitoring using ESP32, RFID, temperature and vibration sensors, an OLED display, Wi-Fi communication, and an alert buzzer.

## Project Limitations

- RFID detection depends on the operating range of the reader.
- The system is designed for indoor asset monitoring.
- GPS-based tracking is not included.

## Project Status

This repository documents the development and proposed design of the Smart Asset Monitoring System as a Final Year Project.

## Author

**Sehshinee Subramaniam**

Diploma Student — Computer Engineering
