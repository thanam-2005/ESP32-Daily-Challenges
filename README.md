# ESP32 LED Blink

A basic embedded systems project that demonstrates **LED control using an ESP32 microcontroller**. The project is programmed using Arduino C/C++ and simulated using the Wokwi platform.

## Overview

The ESP32 is configured to control an LED through a digital GPIO pin. The LED is continuously switched between HIGH and LOW states with a predefined delay, producing a blinking effect.

This project provides a practical introduction to **GPIO configuration, digital output control, and ESP32 programming**.

## Features

* ESP32-based LED control
* Digital GPIO output
* Continuous LED blinking
* Arduino C/C++ implementation
* Wokwi-based circuit simulation
* Simple embedded system implementation

## Technologies Used

* **ESP32**
* **Arduino C/C++**
* **Wokwi Simulator**
* **GPIO**

## Project Structure

```text
ESP32-LED-BLINK/
│
├── sketch.ino
├── diagram.json
├── wokwi-project.txt
├── Light blink.png
└── README.md
```

## Working Principle

```text
ESP32
  │
  │ GPIO Output
  ▼
 LED
  │
  ├── ON
  │
  ├── Delay
  │
  ├── OFF
  │
  └── Delay
       │
       └── Repeat
```

The ESP32 initializes the LED pin as a digital output and repeatedly changes its state to create the blinking effect.

## Simulation

The project is designed and tested using the **Wokwi Simulator**.

The repository contains the ESP32 source code and circuit configuration required to run the simulation.

## Output

The LED continuously switches between **ON and OFF states**, demonstrating digital output control using the ESP32.

## Learning Outcomes

* ESP32 GPIO programming
* Digital output control
* LED interfacing
* Arduino programming
* Embedded systems fundamentals
* Wokwi circuit simulation
* GitHub project management

## Future Enhancements

* Push-button controlled LED
* Multiple LED control
* PWM-based brightness control
* RGB LED control
* Wi-Fi-based LED control
* Web-based ESP32 control

## Repository

[View Source Code](https://github.com/thanam-2005/ESP32-LED-BLINK)
