# Advanced Patient Monitoring System with Disease Prediction

![Patient Analysis System](https://github.com/Ashiksenthil/Automatic-Disease-Prediction-and-Patient-Monitoring-System./assets/119279236/0063250f-190a-4923-ae41-6f9a4b465a00)

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

### Hardware Components
![Hardware Image](https://github.com/Ashiksenthil/Automatic-Disease-Prediction-and-Patient-Monitoring-System./assets/119279236/9c242c88-1f40-478b-97d6-e9cc6bf60420)
The project uses several key hardware components to collect and transmit patient data:

- **Sensors:** Various sensors are employed to gather vital signs from the patient, including heart rate, temperature, and blood pressure.
- **NodeMCU:** This microcontroller unit is used to collect data from the sensors and transmit it wirelessly to the cloud. It features built-in Wi-Fi capabilities, making it ideal for IoT applications.
- **LM35 Temperature Sensor:** An analog temperature sensor used to measure the patient's body temperature with high accuracy.
- **MAX30100 Pulse Oximeter Sensor:** This sensor measures both the pulse rate and the oxygen saturation (SpO2) levels in the blood.
- **LCD Display:** A display module used to show real-time sensor data and system status to the user.

### Software Components

The software aspect of the project includes several components for data collection, processing, and analysis:
![IOT Outcome](https://github.com/Ashiksenthil/Automatic-Disease-Prediction-and-Patient-Monitoring-System./assets/119279236/3e28a306-fe4d-48eb-8d47-9d21000ee026)
- **Arduino IDE:** Used for programming the NodeMCU microcontroller to interface with the sensors and send data to the cloud.
- **ThinkSpeak:** A cloud platform that receives, processes, and stores the data from the NodeMCU. ThinkSpeak allows real-time data streaming and provides tools for data analysis and visualization.
- **Google Colab:** Utilized for developing and running machine learning algorithms to predict potential diseases based on the collected data. The platform offers powerful computational resources and easy integration with datasets.
- **Mobile Application:** A user-friendly application designed for patients to monitor their health data, receive alerts, and communicate with healthcare providers.

### Project Output

The project aims to provide a comprehensive patient monitoring system with the following outputs:
![Outcome Results](https://github.com/Ashiksenthil/Automatic-Disease-Prediction-and-Patient-Monitoring-System./assets/119279236/0e975674-de16-4c01-89aa-ac8d670fdc4c)
- **Real-time Data Monitoring:** Continuous monitoring of patient vitals such as heart rate, temperature, and SpO2 levels, displayed on an LCD screen and accessible via the mobile app.
- **Disease Prediction:** Utilizes machine learning algorithms, specifically the K-Nearest Neighbors (KNN) algorithm, to analyze the collected data and predict potential diseases. This enables early intervention and timely medical care.
- **Alerts and Notifications:** The mobile application sends timely alerts and notifications to patients and healthcare providers, ensuring prompt response to any critical changes in the patient's health status.
- **Data Visualization:** ThinkSpeak provides real-time data visualization, making it easier to track and understand health trends over time.

By integrating these hardware and software components, the project delivers a robust and reliable system for proactive healthcare monitoring and disease prediction.

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

