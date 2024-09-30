[back](../README.md)

# Hardware Developer Specification

This document outlines the tasks and skills required for hardware developers in the Hepheastus Informatics team. As a hardware developer, your primary role will involve creating software and firmware that allow various robotics projects, such as drones, rovers, and other systems, to function properly. Additionally, you’ll be responsible for managing communication between hardware and software layers.

## Key Responsibilities

- Develop and optimize embedded systems and firmware for robotics hardware.
- Implement communication protocols between hardware components and cloud services.
- Test and debug hardware-software interactions.
- Collaborate with the back-end team for real-time data processing and communication.
- Simulate hardware behavior when physical devices are not available using platforms like Wokwi.

## Required Skills

To be successful as a hardware developer, you will need to possess the following skills:

- **Rust/C**: For developing high-performance, low-level code for hardware devices.
- **Embedded Systems**: Knowledge of microcontrollers like Arduino, Raspberry Pi, or ESP32.
- **Communication Protocols**: Understanding of I2C, SPI, UART, and other protocols.
- **Python**: For scripting, automation, and data processing related to hardware devices.
- **Wokwi Simulation**: Ability to simulate Arduino or ESP32 projects virtually.
- **Version Control (Git/GitHub)**: For managing firmware versions and collaborating with the team.

## Suggested Learning Roadmap

Below are tasks designed to help you acquire and develop the necessary hardware development skills.

### 1. Learn Embedded C/Rust for Microcontrollers
   - **Task**: Write a simple program that blinks an LED using C or Rust on a virtual Arduino using [Wokwi](https://wokwi.com/).
   - **Skills Covered**: Basic embedded programming, pin control, timing functions.

### 2. Simulate a Sensor Reading on Wokwi
   - **Task**: Simulate a temperature sensor (like the DHT11) on Wokwi and display the data on a virtual LCD screen.
   - **Skills Covered**: Sensor integration, I2C communication, working with external libraries.

### 3. Learn Python for Scripting & Automation
   - **Task**: Write a Python script that collects data from a virtual sensor on Wokwi and sends it to a remote server (We will do this one together).
   - **Skills Covered**: Python requests library, data handling, HTTP communication with back-end services.

### 4. Implement Communication Protocols (I2C, SPI, UART)
   - **Task**: Simulate communication between two virtual devices on Wokwi using I2C or SPI.
   - **Skills Covered**: Master-slave communication, data transmission protocols.

### 5. Build a Basic Robot Control System
   - **Task**: Using Wokwi, simulate a basic robot that responds to user input to move forward, backward, left, or right.
   - **Skills Covered**: Motor control, UART communication, event-driven programming.

### 6. Integrate Hardware with Cloud Services
   - **Task**: Build a system that collects data from a virtual sensor on Wokwi and sends it to a cloud server for analysis (Once again we will do this one together).
   - **Skills Covered**: IoT principles, HTTP requests, cloud data integration.

