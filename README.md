
# IoT-Based Smart Soil Monitoring and Agricultural Decision Support System

An ESP32-based smart agriculture project for monitoring soil and environmental parameters, with an Edge AI-based crop recommendation approach.

## Project Overview

This project aims to monitor important soil and environmental parameters using an ESP32 microcontroller and multiple sensors. The collected readings are displayed on an OLED display and can be used for agricultural monitoring and decision support.

## Hardware Components

| Component | Purpose |
|---|---|
| ESP32 DevKit V1 | Main microcontroller |
| Capacitive Soil Moisture Sensor | Soil moisture measurement |
| Soil pH Sensor | Soil acidity/alkalinity measurement |
| DHT22 | Ambient temperature and humidity |
| DS18B20 | Temperature measurement |
| 0.96-inch OLED | Display sensor readings |

## Technologies Used

- Embedded C / C++
- ESP32
- Arduino IDE
- Python
- Random Forest Classifier
- Firebase
- IoT / Wi-Fi

## System Architecture

1. Sensors collect soil and environmental parameters.
2. ESP32 reads and processes sensor data.
3. Sensor readings are displayed on the OLED.
4. ESP32 provides the embedded processing and IoT connectivity.
5. The crop recommendation module uses a Random Forest model for crop classification.

## Edge AI Crop Recommendation

The project report describes a Random Forest model with:

- 300 decision trees
- 51 crop classes
- 7 input features
- ESP32-based local inference

Input parameters:
Nitrogen, Phosphorus, Potassium, Temperature, Humidity, Soil pH and Rainfall.

## Hardware Implementation

Add photographs of:
- ESP32 and sensor connections
- Soil moisture and pH sensors
- OLED display output
- Complete hardware prototype

## Project Demonstration

[Watch Project Demonstration](https://drive.google.com/file/d/1jzJN14oFsoIF4RN59JyWAqglHxwtnOYj/view?usp=drive_link)

## Project Documentation

[Download / View Detailed Project Report](https://drive.google.com/file/d/1nMCgtKkmu07SQiwKmJ0nOqakXYfT-TZw/view?usp=drive_link)

## Future Improvements

- NPK sensor integration
- Improved sensor calibration
- Expanded cloud-based monitoring
- Agricultural database integration
- Improved field testing and validation

## Author

Debasis Sau

Electronics and Communication Engineering

GitHub: [Your GitHub Profile](https://github.com/debasissau/Smart-Soil-Monitoring-System/tree/main)
