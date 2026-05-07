# AI-Based Driver Safety & Accident Detection System using IoT

## Overview
This project is an IoT-based driver safety and accident detection system designed to improve road safety using real-time monitoring and sensor-based alerts. The system uses an ESP32 microcontroller along with multiple sensors to detect alcohol presence, abnormal vehicle motion, and accident-related vibrations.

## Features
- Alcohol detection using MQ-3 sensor
- Accident/vibration detection using SW-420 sensor
- Motion and tilt detection using MPU6050
- Real-time buzzer alert system
- Low-cost and compact IoT solution
- Continuous monitoring for driver safety

## Components Used
- ESP32 Microcontroller
- MPU6050 Accelerometer & Gyroscope
- MQ-3 Alcohol Sensor
- SW-420 Vibration Sensor
- Buzzer
- Jumper Wires & Breadboard

## Working
The sensors continuously collect data related to vehicle motion, alcohol vapour, and vibration. The ESP32 processes the sensor readings using threshold-based logic. If any unsafe condition is detected, the system immediately activates a buzzer alert to notify the driver or nearby people.

## Methodology
1. Connect all sensors with the ESP32.
2. Read sensor data continuously.
3. Apply threshold logic for detection.
4. Detect unsafe conditions such as:
   - Alcohol presence
   - Accident vibration
   - Abnormal tilt/motion
5. Trigger buzzer alert when thresholds are exceeded.

## Technologies Used
- IoT
- Embedded Systems
- Arduino IDE
- C/C++ Programming
- Sensor Integration

## Future Scope
- GPS tracking integration
- Cloud data storage
- Mobile application support
- Emergency service notification
- Machine learning-based prediction


## Department
Department of Computer Science and Engineering  
Manav Rachna International Institute of Research and Studies

## License
This project is developed for academic and educational purposes.
