# Edge AI-Based Real-Time Weather Monitoring and Prediction System

## Overview

This project presents an Edge AI-based weather monitoring and prediction system developed using the STM32 Nucleo-F439ZI microcontroller. The system collects real-time environmental data from multiple sensors and performs on-device machine learning inference for weather prediction. The predicted results and sensor readings are transmitted to the cloud using ESP32 and Firebase for remote monitoring and visualization.

## Features

* Real-time environmental data acquisition
* Temperature, humidity, pressure, and rainfall monitoring
* Edge AI-based prediction using STM32Cube.AI
* On-device machine learning inference
* ESP32 Wi-Fi connectivity
* Firebase Realtime Database integration
* Remote monitoring and data visualization
* Low-latency and standalone operation

## Hardware Components

* STM32 Nucleo-F439ZI
* ESP32 Wi-Fi Module
* DHT11 Temperature and Humidity Sensor
* BMP180 Pressure Sensor
* MQ135 Air Quality Sensor
* MQ7 Carbon Monoxide Sensor
* Rain Sensor Module

## Software and Tools

* STM32CubeIDE
* STM32CubeMX
* STM32Cube.AI
* Python
* TensorFlow / Keras
* Firebase Realtime Database
* Arduino IDE

## System Workflow

1. Environmental sensors collect real-time weather data.
2. STM32 acquires and processes sensor readings.
3. Trained machine learning models perform local prediction on the microcontroller.
4. Sensor readings and prediction results are transmitted to ESP32.
5. ESP32 uploads data to Firebase Realtime Database.
6. Python-based visualization tools generate monitoring and performance graphs.

## Machine Learning Models

The system deploys four machine learning models:

* Temperature Prediction
* Humidity Prediction
* Pressure Prediction
* Rainfall Prediction

The models were trained using historical weather datasets and converted into optimized embedded code using STM32Cube.AI.

## Project Outcomes

* Real-time weather monitoring
* Edge AI deployment on STM32 microcontroller
* Cloud-based data logging and visualization
* Reduced dependence on cloud-side computation
* Demonstration of Embedded Systems, IoT, and Edge AI integration

## Author

**Aashvi Atulbhai Gajera**
B.Tech Electronics and Communication Engineering
Sardar Vallabhbhai National Institute of Technology (SVNIT), Surat
