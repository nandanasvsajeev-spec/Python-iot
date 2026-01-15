## 📌 Project Overview

  This project implements a smart classroom temperature monitoring system using IoT technology. The system continuously monitors the classroom temperature and automatically sends a WhatsApp alert to the concerned authority when the temperature exceeds a predefined threshold value (23°C). The solution is designed to be cost-effective, automated, and easy to deploy, making it suitable for educational environments.

The project is implemented using MicroPython and tested using a simulation environment (Wokwi), eliminating the need for physical hardware during development.

## 🎯 Problem Statement

In many classrooms, air conditioning systems operate irregularly, causing discomfort to students. There is often no automated way to monitor classroom temperature or notify authorities in real time. This project addresses that issue by providing an automatic temperature alert system using WhatsApp notifications.

## ⚙️ Features

- Continuous classroom temperature monitoring

- Threshold-based alert system (23°C)

- Automatic WhatsApp notification using API

- WiFi-based communication

- Anti-spam delay mechanism (15-minute cooldown)

- Simulation-based implementation (no hardware required)

## 🧰 Technologies Used

- MicroPython

- ESP32 (Simulated)

- DHT22 Temperature Sensor (Simulated)

- WhatsApp API (TextMeBot / CallMeBot)

- Wokwi Simulator

- GitHub

## 🧩 How the System Works

- The ESP-based controller connects to WiFi.

- The DHT sensor reads temperature and humidity values.

- Temperature values are compared with the threshold (23°C).

- If the temperature exceeds the limit:

- A WhatsApp alert is sent to the registered phone number using an API.

- The system enters a cooldown period of 15 minutes to avoid repeated alerts.

- The process repeats continuously.

## Author
  - [NANDANA SAJEEV] - https://github.com/nandanasvsajeev-spec
  - [MIYANDA MARY JANUSH] - https://github.com/miyandamary?tab=repositories
  - [S.M GOPIKA] - https://github.com/smgopika2-design
  - [ANNA GOMEZ.S] -https://github.com/kmary2575-beep 
