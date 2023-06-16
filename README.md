# Smart Plant Monitoring System

The Smart Plant Monitoring System is a comprehensive solution designed to monitor and manage the health of plants. It utilizes various sensors such as soil moisture, humidity, temperature, and motion to provide real-time data and alerts to users through the Blynk application.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Hardware Requirements](#hardware-requirements)
4. [Software Requirements](#software-requirements)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
The Smart Plant Monitoring System offers a reliable and convenient solution for monitoring and maintaining the health of plants. By integrating various sensors, it continuously collects data on soil moisture, humidity, temperature, and motion. This data is then analyzed and presented to users through the Blynk application, enabling them to make informed decisions and take appropriate actions to ensure optimal plant growth.

## Features
- Real-time Monitoring: Continuously monitors soil moisture, humidity, temperature, and motion of the plants.
- Blynk Application Integration: Provides a user-friendly interface for accessing real-time data, receiving alerts, and controlling the system remotely.
- Alert System: Notifies users through the Blynk application when the plant requires water or detects any unusual motion.
- Automatic Watering: Automatically activates the water pump when the soil moisture level is low, ensuring plants receive adequate hydration.
- Motion Sensor Control: Allows users to enable or disable the motion sensor through the Blynk application, providing flexibility in monitoring and conserving power.
- Data Analysis: Enables users to analyze historical data trends and gain insights into the plant's growth and environmental conditions.

## Hardware Requirements
To set up the Smart Plant Monitoring System, you will need the following components:
- ESP32 or compatible microcontroller
- Soil moisture sensor
- DHT11 or similar temperature and humidity sensor
- Motion sensor
- Water pump
- LCD display (optional)
- Jumper wires and breadboard

## Software Requirements
The following software tools are required for setting up the project:
- Arduino IDE or compatible development environment
- Blynk application (available for Android and iOS)
- Blynk library for Arduino
- DHT library for Arduino (if using DHT11 sensor)
- ESP32 board support package for Arduino IDE

## Installation
1. Connect the components according to the circuit diagram provided.
2. Install the Arduino IDE and necessary board support package.
3. Install the required libraries for Arduino.
4. Set up the Blynk application and create a new project.
5. Obtain the authentication token from the Blynk project.
6. Open the Arduino IDE, load the sketch, and configure the necessary settings.
7. Upload the sketch to the ESP32 board.

## Usage
1. Power on the Smart Plant Monitoring System.
2. Open the Blynk application and connect to the project using the authentication token.
3. Monitor the real-time data displayed on the Blynk application.
4. Receive alerts and notifications regarding plant watering requirements and motion detection.
5. Adjust the watering schedule or enable/disable the motion sensor as needed.
6. Analyze historical data trends and make informed decisions for optimal plant care.

## Contributing
Contributions to this project are welcome. Feel free to submit bug reports, feature requests, or pull requests to the project repository.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to modify and distribute it according to the terms of the license.
