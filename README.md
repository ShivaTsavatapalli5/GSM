# GSM Communication for Person Detection Alerts

## Overview
This section outlines the GSM communication system used to send alerts when a person is detected. The GSM 900A MINI module enables the transmission of SMS messages containing the GPS coordinates of detected individuals, facilitating quick responses in critical situations.

## Hardware
- **SIM900A MINI GSM Module**: This module is responsible for sending SMS .

## Setup and Configuration

### Requirements
- A working GSM SIM card with SMS capabilities.
- Ensure the SIM900A MINI GSM module is connected to the Raspberry Pi or compatible microcontroller.

### Wiring
- Connect the GSM module to the Raspberry Pi as follows:
  - **VCC** to a suitable power supply (typically 5V).
  - **GND** to ground.
  - **TX** (transmit) pin to a GPIO pin configured for receiving data.
  - **RX** (receive) pin to a GPIO pin configured for sending data.

### Software Installation
1. Ensure the necessary libraries for serial communication are installed. You can install `pyserial` using pip:
   ```bash
   pip install pyserial
