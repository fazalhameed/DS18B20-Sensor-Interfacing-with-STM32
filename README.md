# DS18B20 Sensor Interfacing with STM32

This repository contains code and resources for interfacing the DS18B20 temperature sensor with an STM32 microcontroller. The DS18B20 is a popular digital temperature sensor that communicates using the 1-Wire protocol.

## Features
- Accurate temperature readings from the DS18B20 sensor.
- 1-Wire protocol implementation on STM32.
- Temperature values are displayed on the serial monitor via USART.

## Prerequisites
- STM32 microcontroller ( STM32G0 ).
- DS18B20 temperature sensor.
- IDE and tools for STM32 development ( STM32CubeIDE).
- USB-to-serial adapter or a built-in serial communication feature.

## Hardware Setup
1. Connect the DS18B20 data pin to a GPIO pin on the STM32.
2. Use a pull-up resistor (4.7kΩ) between the data pin and VCC (3.3V or 5V).
3. Power the DS18B20 sensor with VCC and GND.
4. Connect the STM32 USART pins to your PC via a USB-to-serial adapter (TTL).

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/fazalhameed/DS18B20-Sensor-Interfacing-with-STM32.git
