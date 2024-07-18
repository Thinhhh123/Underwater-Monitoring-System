# Thesis_Report


# Underwater Monitoring System


## Overview
This repository contains all the code, data, and documentation related to the thesis on the development of an underwater monitoring system. The system integrates an Arduino-based safety tracking subsystem and a Raspberry Pi-based high-level processing subsystem. It collects real-time environmental data, controls LED lighting, processes images, and uploads data to remote servers.

## Features

- **Real-Time Environmental Monitoring**: Collects data on temperature, humidity, current, and voltage.
=======
- **Real-Time System Performance Tracking**: Collects data on temperature, humidity (System environment) - Current & Voltage of System.

- **LED Lighting Control**: Adjusts lighting for optimal camera performance in low-light conditions.
- **Image Processing**: Uses the OAK-D AI camera for fish detection and counting.
- **Remote Data Monitoring**: Uploads data to ThingSpeak and Firebase for remote access.

## Repository Structure
- **Arduino_Code/**: Contains Arduino sketches for sensor readings, safety tracking, and LED control.
- **RaspberryPi_Code/**: Python scripts for image processing, camera control, and data upload.
<<<<<<< HEAD
- **Data/**: Collected sensor and image data.
- **Documentation/**: Thesis document, system architecture, and flowcharts.
- **Hardware_Design/**: Enclosure design files, wiring diagrams, and bill of materials.
=======
- **Data/**: Collected sensor and transmit to Rasbberry Pi.
- **Documentation/**: Thesis document, system architecture, and flowcharts.
- **Hardware_Design/**: Enclosure design files, wiring diagrams.
## Hardware Setup

![image](https://github.com/user-attachments/assets/efbc9689-1087-434f-8160-e0881b1933ba)

![image](https://github.com/user-attachments/assets/a83497e6-4e33-4f48-bd8a-4d5721ecf130)

![image](https://github.com/user-attachments/assets/3271ae14-2e3d-4f12-8714-b21179ff093c)



## Workflow Diagram

![image](https://github.com/user-attachments/assets/69252219-7145-4dbf-ac0f-2307be2de832)



## Getting Started
### Prerequisites
- Arduino IDE
<<<<<<< HEAD
- Python 3.x
=======
- Python 3.9

- Required Python libraries: OpenCV, numpy, requests
- ThingSpeak and Firebase accounts

### Installation
1. **Arduino Setup**: Upload the sketches from the `Arduino_Code/` directory to the Arduino Uno.
2. **Raspberry Pi Setup**: Install the required Python libraries and run the scripts from the `RaspberryPi_Code/` directory.

### Usage
- **Data Collection**: Run the Arduino sketches to start collecting sensor data.
- **LED Control**: Adjust the LED settings as needed using the Arduino.
- **Image Processing**: Run `Image_Processing.py` on the Raspberry Pi to start processing images.
<<<<<<< HEAD
- **Sensor Data Upload**: Use `thingsSpeakAPI.py` to upload data to ThingSpeak
=======
- **Image Capturing and Uploading**: Use `Image_processing_uploading.py` to capture and upload processing images to Firebase.

## Contributing
Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Arduino](https://www.arduino.cc/)
- [Raspberry Pi](https://www.raspberrypi.org/)
- [ThingSpeak](https://thingspeak.com/)
- [Firebase](https://firebase.google.com/)
