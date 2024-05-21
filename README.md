# Advanced Patient Monitoring System with Disease Prediction

![Patient Analysis System](./path/to/your/image/Screenshot 2024-05-21 161957.png)

## Introduction

This project implements an advanced patient monitoring system that leverages IoT and machine learning technologies to provide continuous and proactive healthcare solutions. The system uses sensors to collect essential patient data, which is then analyzed to predict potential diseases and provide timely medical recommendations.

## Features

- **Real-time Monitoring:** Utilizes wireless sensors to gather vital data such as heart rate, temperature, and blood pressure.
- **Disease Prediction:** Employs machine learning algorithms to forecast potential diseases based on collected data.
- **User-Friendly Interface:** A mobile application for patients to receive alerts and communicate with healthcare providers.
- **Data Visualization:** Presents data and predictions in an easy-to-understand format.

## System Components

1. **Sensors:** Collects patient's vital signs.
2. **NodeMCU:** Transfers data to the cloud.
3. **ThinkSpeak Cloud Platform:** Stores and processes data in real-time.
4. **Machine Learning Model:** K-Nearest Neighbors (KNN) algorithm for disease prediction.
5. **Mobile Application:** Interfaces with the system to alert patients and healthcare providers.

## Project Structure

- `hardware/` - Contains the design and implementation of the hardware components.
- `software/` - Includes the code for data collection, processing, and machine learning algorithms.
- `mobile_app/` - The source code for the patient-facing mobile application.
- `documentation/` - Project documentation and reports.

## Getting Started

### Prerequisites

- NodeMCU
- LM35 Temperature Sensor
- MAX30100 Pulse Oximeter Sensor
- LCD Display
- Arduino IDE
- ThinkSpeak Account
- Google Colab for Machine Learning

### Installation

1. **Hardware Setup:** Assemble the sensors and connect them to the NodeMCU as per the circuit diagram provided in the documentation.
2. **Software Setup:** 
   - Install the necessary libraries in Arduino IDE.
   - Upload the code to NodeMCU.
3. **Machine Learning Model:**
   - Use Google Colab to train the KNN model with the dataset.
   - Deploy the model to ThinkSpeak for real-time predictions.
4. **Mobile Application:** Install the app on your mobile device and configure it to connect with the ThinkSpeak channel.

## Usage

- Start the NodeMCU to begin data collection.
- Monitor the real-time data and predictions on the mobile application.
- Receive alerts and take necessary actions as recommended by the system.

## Contribution
- Ashik S: [ashik.optimist@gmail.com](mailto:ashik.optimist@gmail.com)
- Bala Subramaniyan S
- Dharanishan K
- Ganeshraja A

