# PIXLED Bluetooth Demo

PIXLED Bluetooth Demo is a project that demonstrates a custom Bluetooth application with a WS2811 LED strip. It is based on the NimBLE_Server Demo written by H2zero.

## Table of Contents

- [PIXLED Bluetooth Demo](#pixled-bluetooth-demo)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Code Structure](#code-structure)
  - [Customization](#customization)
  - [Troubleshooting](#troubleshooting)
  - [Contributing](#contributing)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Introduction

PIXLED Bluetooth Demo showcases the integration of Bluetooth functionality with a WS2811 LED strip using the NimBLE library. It enables users to control LED brightness, color, and state via a Bluetooth connection.

## Features

- Bluetooth integration with WS2811 LED strip.
- Control LED brightness, color, and state.
- Automatic LED strip initialization upon connection.
- Supports multiple simultaneous Bluetooth connections.

## Requirements

- ESP32 platform.
- Arduino IDE or compatible development environment.
- FastLED library.
- NimBLE library.

## Installation

1. Clone the repository.
2. Open the project in Arduino IDE.
3. Install the required libraries (FastLED, NimBLE).
4. Upload the code to your ESP32 device.

## Usage

1. Power on the ESP32 with the LED strip connected.
2. Connect the data pin the corresponding GPIO (e.g. GPIO2 in this example)
3. Connect to the device via Bluetooth.
4. Control LED brightness, color, and state using a compatible Bluetooth application.

## Code Structure

The main code is organized into tasks for Bluetooth and LED control. The project uses NimBLE for Bluetooth communication and FastLED for LED control.

## Customization

Users can customize LED behavior, Bluetooth characteristics, and other parameters by modifying the relevant sections in the code.

## Troubleshooting

If issues arise, refer to the [Troubleshooting](#troubleshooting) section in the code.

## Contributing

Contributions are welcome. Follow the guidelines in the [Contributing](#contributing) section in the code.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

## Acknowledgments

- H2zero for the NimBLE_Server Demo.
- FastLED community for the LED control library.