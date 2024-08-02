# IoT-Based Fall Detection System Using NodeMCU ESP8266 & MPU6050
This project implements an IoT-based fall detection system using NodeMCU ESP8266 and MPU6050. When a fall is detected, an alert is sent via SMS using the IFTTT platform.

# Components Required
    NodeMCU ESP8266
    MPU6050 Accelerometer and Gyroscope
    Breadboard and jumper wires
    Power supply
    Circuit Diagram

# Install required libraries:
MPU6050
ESP8266WiFi
Upload the code to NodeMCU:

Open fall_detection.ino in Arduino IDE.
Configure your WiFi credentials.
Upload the code to the NodeMCU.
IFTTT Setup
Create an IFTTT account and set up a new applet.
Trigger: Choose Webhooks service and configure it with the event name fall_detected.
Action: Choose SMS service and set the recipient phone number.
Code
Refer to the fall_detection.ino file for the complete code.

How It Works
The MPU6050 sensor detects sudden changes in motion indicative of a fall. When a fall is detected, the NodeMCU sends a trigger to IFTTT, which then sends an SMS alert.
