🌞 Solar-Powered Smart Irrigation System (Mobile App Controlled)

A Sustainable, IoT-Based Water Management Solution

📘 Overview

This project implements a fully automated solar-powered irrigation system integrated with an IoT mobile application.
It monitors soil moisture, water levels, temperature, and humidity in real-time and controls the water pump either automatically or manually through a mobile app.

The system is engineered for:

Agriculture

Vertical farming

Remote farms

Water-limited areas

Designed with efficiency, sustainability, and real-time responsiveness at its core.

⚡ Key Features
1. Solar-Powered Operation

The irrigation system is powered using photovoltaic panels.

Maximizes energy efficiency and ensures continuous operation in remote locations.

2. IoT Mobile Application Control

Users can monitor all sensor values from a smartphone:

Soil moisture levels

Water level status

Temperature

Humidity

Manual ON/OFF control for the pump.

Auto Mode that waters plants without human intervention.

3. Smart Automatic Irrigation

AI-inspired logic monitors soil moisture and triggers watering only when required.

Prevents water wastage and ensures plant health.

4. Real-Time Monitoring

Uses Blynk IoT cloud for:

Live data display

Notifications

Remote accessibility

5. Safety & Efficiency

Pump operation blocked when water levels are low.

Solar-charged battery ensures 24/7 uptime.

🛠 Hardware Components

ESP32 microcontroller

Solar panel (10W–25W recommended)

Battery + Solar Charge Controller

Soil Moisture Sensor

DHT11 / DHT22 Sensor (Temperature & Humidity)

Water Level Sensor

Relay Module (for pump control)

Water Pump (12V DC or AC with proper isolation)

Jumper wires, pipes, connectors

🧠 Software & Cloud

Arduino IDE

Blynk IoT Platform

ESP32 WiFi Library

DHT Sensor Library

Real-time cloud dashboards

📲 Mobile App Features (Blynk)
Function	Virtual Pin	Description
Soil Moisture	V0	Filtered percentage value
Water Level	V1	Tank full/empty indicator
Temperature	V2	°C measurement
Humidity	V3	% RH
Pump Status	V4	Current pump state
Auto/Manual Mode	V5	Switch mode
Manual Pump Control	V6	Button control
🚀 How It Works

Sensors collect environmental data.

ESP32 processes the data and sends it to the Blynk cloud.

Auto Mode:

Pump turns ON when soil moisture drops below threshold.

Pump turns OFF when moisture recovers or water level is low.

Manual Mode:

User directly controls the pump via the smartphone.

Solar panel charges the battery → system stays online 24/7.

📡 Future Enhancements

AI-based prediction of irrigation cycles

Weather API integration

Automated fertilizer distribution

LoRa-based long-range version for large farms

LCD/Touchscreen local dashboard

📁 Folder Structure
Solar-Irrigation/
│── src/
│     └── solar-irrigation.ino
│── README.md
│── .gitignore
│── wiring-diagram.png (optional)
│── secrets.example.h

🧾 License

This project is open-source and free to modify for educational or commercial use.
