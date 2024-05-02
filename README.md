# Advanced Patient Monitoring and Disease Prediction System

This repository contains the code and documentation for the Bachelor of Engineering final year project titled "Advanced Patient Monitoring and Disease Prediction System Using Machine Learning", developed by Ashik S, Bala Subramaniyan S, Dharanishan K, and Ganeshraja A at Sri Eshwar College of Engineering.

## Project Overview

The project aims to enhance patient monitoring and disease prediction using a combination of Internet of Things (IoT) and machine learning technologies. The system collects physiological data using sensors and predicts possible diseases using a K-Nearest Neighbors algorithm.

## Features

- **Real-Time Monitoring**: Utilizes ESP8266 module for real-time data collection.
- **Disease Prediction**: Employs machine learning (KNN algorithm) to predict diseases based on sensor data.
- **Cloud Integration**: Uses ThingSpeak for data aggregation and analysis.
- **User Interface**: Simple and intuitive display on LCD.

## Hardware Components

- NodeMCU
- MAX30100 Pulse Oximeter
- LM35 Temperature Sensor
- LCD Display
- ESP8266 WiFi Module

## Software Requirements

- Arduino IDE for microcontroller programming.
- ThingSpeak for data storage and analysis.
- Python for machine learning and prediction.
- Google Colab for executing machine learning models.

## Setup and Installation

1. **Hardware Setup**: Assemble the hardware components based on the circuit diagrams provided in the `hardware` directory.
2. **Software Installation**:
   - Install Arduino IDE and configure the ESP8266 board.
   - Setup a ThingSpeak channel for collecting sensor data.
   - Prepare the Python environment in Google Colab for running the prediction models.

## Usage

1. Power on the system and ensure it is connected to the internet through WiFi.
2. The system will start collecting data and display it on the LCD.
3. Data is sent to ThingSpeak for storage and analysis.
4. The prediction results are calculated and displayed on the LCD and also can be viewed in the ThingSpeak channel.


## Authors

- **Ashik S** - [AshikS](https://github.com/AshikS)
- **Bala Subramaniyan S** - [BalaS](https://github.com/BalaS)
- **Dharanishan K** - [DharanishanK](https://github.com/DharanishanK)
- **Ganeshraja A** - [GaneshrajaA]

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

- Hat tip to anyone whose code was used

