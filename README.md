# Arduino Radar System

This project is a simple Radar System built using Arduino, an ultrasonic sensor, and a servo motor. It scans the surrounding area and detects objects by measuring the distance using ultrasonic waves. The detected objects are then visualized on a radar-like interface.

## Project Overview
The system rotates an ultrasonic sensor using a servo motor to scan the environment from 0° to 180°. When an object comes within the sensor’s range, the distance is measured and displayed on the radar interface. This creates a visualization similar to how real radar systems detect objects.

## Components Used
- Arduino Uno
- Ultrasonic Sensor (HC-SR04)
- Servo Motor
- Jumper Wires
- Breadboard
- Computer with Arduino IDE

## How It Works
1. The servo motor rotates the ultrasonic sensor from 0° to 180°.
2. The ultrasonic sensor sends sound waves and waits for the echo.
3. The Arduino calculates the distance of any object detected.
4. The data is sent to the computer.
5. A radar-style visualization shows detected objects on the screen.

## Applications
- Basic object detection systems
- Robotics projects
- Learning embedded systems and sensors
- Educational demonstrations

## Installation and Setup
1. Connect all components according to the circuit diagram.
2. Open the Arduino code in Arduino IDE.
3. Select the correct board and port.
4. Upload the code to the Arduino.
5. Run the visualization program to see the radar display.

## Future Improvements
- Increase detection range
- Improve radar visualization
- Add wireless data transmission
- Integrate with IoT platforms

## Project Repository
You can find the full project here:
https://github.com/satyamkumarsoni111/Radar_System

## Author
Satyam Soni  
BTech CSE (AI/ML)
