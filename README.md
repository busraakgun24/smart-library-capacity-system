# smart-library-capacity-system
Microcontroller-free library occupancy tracking system using digital logic ICs, up/down counters, seven-segment displays, circuit simulations, and a physical prototype.
Smart Library Capacity Tracking and Occupancy Alert System
A team-based digital logic design project developed by Büşra Akgün and İlayda Kaya at Balıkesir University, Department of Computer Engineering.
Project Overview
The Smart Library Capacity Tracking and Occupancy Alert System is a hardware-based project designed to track library occupancy using digital logic circuits.
The proposed system counts people entering and leaving a library, displays the current count on a two-digit seven-segment display, and aims to provide a visual warning when a predefined capacity limit is reached.
The project explores a microcontroller-free approach using digital logic integrated circuits rather than Arduino or embedded software.

Project Objectives
- Design an up/down counting system for tracking occupancy.
- Display the current count using two seven-segment displays.
- Explore infrared sensor inputs and manual push-button controls.
- Design logic-based capacity detection and visual status indicators.
- Investigate the practical challenges of implementing digital logic circuits in physical hardware.
Hardware Components
The design and implementation process involved the following components:
- 74LS192: Presettable up/down counter
- 74LS47: BCD-to-seven-segment decoder/driver
- Seven-segment displays: Digital count visualization
- 74LS08: AND logic gates
- 74LS04: NOT logic gates
- NE555 timer and 74HC14 Schmitt trigger: Timing and signal-conditioning approaches explored during development
- Infrared sensor modules and push buttons
- Resistors, capacitors, breadboards, and a power supply module
Tools and Simulation
- Logisim
- Tinkercad Circuits
- Physical breadboard prototyping
Design and Implementation
The project progressed through circuit design, simulation, physical assembly, and hardware troubleshooting.
The counting circuit was designed around 74LS192 up/down counters, with 74LS47 decoder ICs driving the seven-segment displays.
Simulation activities were used to investigate the counting logic and display behavior. A physical prototype was also assembled and tested on a breadboard.
During physical testing, a count of up to 99 was observed. However, stable continuous operation was not achieved because of hardware-related issues, including unreliable breadboard connections, display pinout differences, and power instability.
Challenges and Troubleshooting
The development process involved investigating several practical engineering challenges:
- Unstable input signals and floating logic states.
- Display and decoder compatibility.
- Breadboard connection and contact problems.
- Power supply protection triggered during hardware testing.
- Differences between simulation behavior and physical implementation.
These challenges and the troubleshooting attempts are documented in the project report.
Teamwork and Collaboration
Team members:
- Büşra Akgün
- İlayda Kaya
This project was developed collaboratively as part of the Digital Design Laboratory course at Balıkesir University.
The work involved circuit design, simulation, hardware assembly, testing, and technical documentation.
Project Documentation
The repository contains the available project documentation and supporting materials:

- docs/ – Project reports
- images/ – Physical prototype and circuit screenshots
- simulation/ – Available simulation files
- videos/ – Demonstration videos or links to test recordings
## Project Status
Academic team project completed as a course project. The design, simulations, physical prototyping, and troubleshooting process were documented. Further hardware revisions and testing would be needed to achieve reliable continuous operation.
