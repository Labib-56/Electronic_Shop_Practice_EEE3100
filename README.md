# Electronic Shop Practice — EEE 3100

## About the Course

**EEE 3100 — Electronics Shop Practice**  
**Department of Electrical & Electronic Engineering**  
**Rajshahi University of Engineering & Technology (RUET)**  
**Bangladesh**

Electronics Shop Practice is a hands-on laboratory course in the undergraduate EEE curriculum at RUET. It bridges the gap between theoretical knowledge and real-world engineering by having students work directly with electronic components, tools, and embedded systems. The course spans three broad areas:

**Electronics Design** — Component selection, tolerances, passive component characteristics, analogue interface to digital circuits, noise analysis and modelling, EMC, grounding strategies, and signal integrity.

**Advanced Components and Sensors** — Introduction to microcontroller interfacing (IR, PIR, ultrasonic, sonar, humidity sensors, etc.), robotics and automation, Introduction to IoT and its applications, ARM processors, STM32, various IoT modules (ESP32, ADC/DAC modules, etc.).

**PCB Design** — Construction and manufacturing of printed circuit boards using CAD tools, schematics, simulation, layout, soldering, testing, and mechanical construction including enclosures.

The course culminates in a group or individual engineering project that involves producing specifications, detailed design, prototype production, and testing. The design is presented orally and documented in formal technical reports considering scheduling, marketing, and business plans.

---

## Repository Structure

This repository contains all project reports and documentation completed throughout the course, divided into two parts:

- **Part I — Course Projects (01–10):** Ten structured lab/mini-projects covering progressively advanced topics in electronics, microcontrollers, robotics, and sensors.
- **Part II — Final Project:** A final project that integrates the skills developed throughout the course.

---

## Part I — Course Projects

### Project 01 — Soldering & Testing of Astable Multivibrator
Hands-on soldering practice using a classic astable multivibrator circuit. Covers component identification, PCB soldering technique, and oscilloscope-based waveform verification.

### Project 02 — PCB Design and Soldering a Charger Circuit
Designed and fabricated a battery charger circuit PCB from scratch. Covers schematic capture, PCB layout using CAD tools, etching, drilling, and soldering.

### Project 03 — Hands-On Projects with Arduino Microcontroller
Introduction to the Arduino microcontroller platform. Covers digital I/O, PWM, analog reading, and basic programming — the foundation for all subsequent embedded projects.

### Project 04 — Implementation of a Robotic System Using the L293D Motor Driver IC
Built a basic robot chassis controlled via the L293D H-bridge motor driver IC. Covers DC motor control, direction and speed regulation using PWM signals from Arduino.

### Project 05 — IR-Guided Line Follower Robot Using Arduino
Designed and built a line-following robot using infrared (IR) sensors. The robot autonomously follows a black line on a white surface by reading IR sensor feedback and adjusting motor speeds in real time.

### Project 06 — Line Following and Obstacle Avoidance Robot
Extended the line follower with ultrasonic obstacle detection. The robot follows a line and dynamically stops or reroutes when an obstacle is detected within a threshold distance.

### Project 07 — Voice-Controlled Home Automation System Using HC-05 and Arduino
Implemented a home automation prototype where appliances are controlled via voice commands over Bluetooth. An Android app sends voice-to-text commands to the Arduino via the HC-05 Bluetooth module.

### Project 08 — Digital Voltmeter Using Arduino
Built a digital voltmeter that reads an input voltage via the Arduino's ADC, applies a voltage-divider calibration formula, and displays the result on a 16×2 LCD screen.

### Project 09 — Microcontroller Interfacing of Dual-Axis Joystick Module
Interfaced a dual-axis analog joystick with Arduino. Reads X and Y potentiometer values via ADC and maps them to directional or servo control outputs.

### Project 10 — Motor Control Using Temperature Sensor
Implemented a temperature-responsive motor speed controller. An NTC thermistor reads ambient temperature; the Arduino maps the temperature reading to a PWM signal to drive a DC fan at proportional speed.

---

## Part II — Final Project

### Smart Mobile Robot with Real-Time Object Detection Using TensorFlow Lite

A fully autonomous smart robot that navigates its environment and performs real-time object detection using a camera and a TensorFlow Lite model running on an embedded processor.

**Key Capabilities:**
- 🤖 Autonomous mobile platform with DC motor drive and H-bridge control
- 📷 On-board camera for live video capture
- 🧠 Real-time object detection using a pre-trained TensorFlow Lite MobileNet SSD model
- 📡 Wireless communication for remote monitoring or teleoperation
- ⚡ Embedded deployment — no cloud dependency, inference runs entirely on device

**Tech Stack:**

| Component | Detail |
|---|---|
| Platform | Raspberry Pi Zero 2W |
| Framework | TensorFlow Lite |
| Model | MobileNet SSD (pre-trained, quantized) |
| Motor Driver | L298N / L293D H-bridge |
| Sensor | Pi Camera |
| Communication | Wi-Fi / Bluetooth |

---

## Project Info

- **Student:** Labib Marwan Hoque (Roll: 2101064)
- **Department:** Electrical & Electronic Engineering, RUET
- **Course:** EEE 3100 — Electronics Shop Practice
