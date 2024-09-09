# Solar Tracker Project
# Overview
This project is a Solar Tracker system built using an Arduino Mega. The Solar Tracker automatically positions a solar panel to face the direction that maximizes the amount of sunlight it receives throughout the day. By doing so, it optimizes the energy output of the solar panel, making it more efficient than a stationary setup.
# Features: 
Dual-Axis Tracking: Tracks the sun in both horizontal and vertical axes for maximum sunlight exposure.
Real-time Positioning: Continuously adjusts the solar panel's position based on the sun's movement.
Light Sensors: Utilizes LDR (Light Dependent Resistors) to detect sunlight intensity from different directions.
Efficient Energy Use: Minimizes energy consumption while maximizing energy output from the solar panel.
Arduino Mega Powered: The entire system is controlled by an Arduino Mega microcontroller, providing ample I/O pins and processing power for the task.

# Components
Arduino Mega 2560
Servo Motors (2x)
LDR Sensors (4x)
Solar Panel
Motor Driver Module
Breadboard and Jumper Wires
Power Supply (e.g., 12V battery or solar power)
Mounting Frame for Solar Panel

# Circuit Diagram

# Installation
# Clone the Repository:


https://github.com/Nizamthakur/Solar_Tracker.git
cd Solar_Tracker
# Upload the Code to Arduino:

Open the solar_tracker.ino file in the Arduino IDE.
Connect your Arduino Mega to your computer.
Select the correct board and port in the Arduino IDE.
Upload the code to the Arduino.
Build the Circuit:

Assemble the components according to the provided circuit diagram.
Connect the servo motors, LDR sensors, and solar panel as indicated.
Power the System:

Connect the Arduino Mega to your power source.
Ensure that the solar panel is mounted securely and can rotate freely in both axes.

# Usage
Once powered on, the Solar Tracker will begin automatically adjusting the solar panel to face the sun. The LDR sensors continuously monitor sunlight intensity, and the Arduino Mega calculates the optimal position for the solar panel, moving the servo motors as needed.

# Code Explanation
LDR Sensor Reading: The LDRs provide analog input values based on the amount of light they receive. These values are used to determine the direction with the most sunlight.
Servo Control: The servos are controlled via PWM signals from the Arduino Mega, adjusting the panel's orientation.
Position Calculation: The difference in readings between the LDRs is used to calculate the required adjustments for both axes.

 
