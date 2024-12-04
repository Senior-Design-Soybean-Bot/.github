# Senior Design Soybean Bot

Welcome to the Senior Design Soybean Bot project! This organization hosts repositories related to the development and operation of a robotic system designed for soybean field monitoring and data collection.

## Repositories

### 1. Soybean-Jetson

- **Description**: This repository contains a ROS2 package for controlling the robot remotely. It includes functionalities for taking pictures and geo-tagging them, which is essential for field data collection and analysis.
- **Technologies Used**: ROS2, NVIDIA Jetson platform.
- **Usage**: The package is designed to be deployed on a Jetson device, enabling remote operation and data acquisition in agricultural settings.

### 2. Soybean-ino

- **Description**: This repository includes files uploaded to the Arduino for the Soybean robot. It contains the necessary code to interface with the robot's hardware components.
- **Technologies Used**: Arduino, C++.
- **Usage**: The code is intended to be flashed onto the Arduino microcontroller, which manages the robot's sensors and actuators.

## Getting Started

To get started with the Soybean Bot project, you will need to set up the development environment for both the Jetson and Arduino platforms. Detailed setup instructions can be found in the respective repositories.

### Prerequisites

- **Jetson Platform**: Ensure you have a compatible NVIDIA Jetson device with ROS2 installed.
- **Arduino**: An Arduino board compatible with the provided code.

### Installation

1. Clone the repositories:
   ```bash
   git clone https://github.com/Senior-Design-Soybean-Bot/Soybean-Jetson.git
   git clone https://github.com/Senior-Design-Soybean-Bot/Soybean-ino.git
   ```

2. Follow the setup instructions in each repository to configure your development environment.
