# Using-MQ2-Gas-Sensor-to-Remotely-Detect-Location-of-Excessive-Gas-Concentration
This repository contains the implementation for a robust gas detection system using the MQ2 gas sensor and Raspberry Pi Pico microcontroller boards. The system is designed to detect various gases like methane, propane, and smoke, ensuring safety in both industrial and domestic environments.

## Overview

This project implements a remote gas detection system using the MQ2 gas sensor and Raspberry Pi Pico boards. The system aims to detect various gases like methane, propane, and smoke, providing real-time monitoring capabilities to ensure safety in industrial and domestic environments.

## Features

- **MQ2 Gas Sensor:** Utilizes gas conductivity to measure and detect concentrations of different gases.
- **Remote Monitoring:** Enables real-time monitoring of gas concentration levels remotely via Wi-Fi communication between Raspberry Pi Pico boards.
- **Raspberry Pi Pico:** Harnesses the RP2040 microcontroller chip's capabilities for efficient data processing and transmission.
- **Safety Focus:** Designed to prevent potential hazards associated with gas leakages, including fire, explosions, and health risks.

## Setup

### Hardware Requirements

- MQ2 Gas Sensor
- Raspberry Pi Pico (two boards)
- Neo 6M GPS Sensor
- Jumper wires, breadboards, display monitor, LED bulbs, etc.

### Installation Steps

1. **Circuit Connection:** Refer to the circuit diagrams provided in the `/diagrams` directory for proper sensor and board connections.
2. **Code Deployment:** Use the source code in the `/code` directory to program the Raspberry Pi Pico boards for data acquisition and transmission.

## Usage

1. Upload the respective code to each Raspberry Pi Pico board.
2. Power up the system and ensure proper connectivity between the boards and the gas sensor.
3. Access the monitoring interface through the designated IP address or interface provided in the documentation.

## Contributing

Contributions and enhancements to this project are welcome! Please fork the repository, make improvements, and submit pull requests to help enhance the system's functionality and efficiency.

## Acknowledgments

This project was co-created by Kaustubh Singh ()
