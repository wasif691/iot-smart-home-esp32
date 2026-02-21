Smart Home Automation System
A cloud‑connected smart home automation system built using ESP32, Firebase Realtime Database, and a Mobile App. The system enables users to remotely control home appliances and monitor sensor data in real time.

Project Overview
This project provides a complete IoT‑based smart home solution where users can:

Control appliances such as lights, fan, and water pump

Monitor temperature, humidity, and water level

Automate the water pump based on tank level

Access the system from anywhere using a mobile app

Sync all data through Firebase in real time

The ESP32 acts as the main controller, communicating with Firebase to read commands and update sensor values.

Features
Real‑time device control

Cloud‑based data synchronization

Water level monitoring

Temperature and humidity monitoring

Automatic water pump control

Mobile app dashboard

Secure communication using Firebase rules

ESP32‑based hardware control

System Architecture
Mobile App → Sends ON/OFF commands and displays sensor data

Firebase Realtime Database → Stores device states and sensor values

ESP32 → Reads Firebase values and controls relays

Sensors → Send real‑time data back to Firebase

Hardware Components
ESP32 Development Board

Relay Module

DHT11 / DHT22 Sensor

Water Level Sensor

Light Bulb / Fan / Water Pump

Power Supply

Software and Tools
Arduino IDE or PlatformIO

Firebase Realtime Database

Android App (Flutter, MIT App Inventor, or Java)

C/C++ for ESP32 firmware
