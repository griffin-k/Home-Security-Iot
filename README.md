# Home-Security-IoT

## Overview
Home-Security-IoT enhances home security using ESP32-CAM, servo, solenoid lock, laser, and LDR module. The web interface, built with HTML, JavaScript, and Tailwind CSS, provides real-time monitoring. The system detects and recognizes individuals using OpenCV Python. Known individuals can unlock the door using the solenoid lock, while unknown individuals trigger the alarm system. Laser security triggers an alarm when interrupted, with all statuses displayed on the website.

## Tech Stack

### Hardware Components
- **ESP32-CAM:** Captures video feed and performs facial recognition.
- **Servo Motor:** Controls the door lock.
- **Solenoid Lock:** Locks and unlocks the door.
- **Laser and LDR Module:** Provides security by detecting interruptions.
- **Webcam:** Captures video feed for facial recognition.

### Software Components
- **OpenCV Python:** Used for facial recognition.
- **HTML, JavaScript, Tailwind CSS:** Develops the web interface for real-time monitoring and control.
- **C++:** Develops the hardware code for ESP32-CAM.

## Features
- **Facial Recognition:** Uses OpenCV Python to detect and recognize individuals.
- **Door Access Control:** Known individuals can unlock the door using the solenoid lock.
- **Alarm System:** Triggers an alarm for unknown individuals.
- **Laser Security:** Triggers an alarm when the laser beam connection is interrupted.
- **Real-time Monitoring:** Displays all statuses on the web interface in real-time.

## Usage
1. ESP32-CAM captures video feed and performs facial recognition.
2. Known individuals can unlock the door using the solenoid lock via the web interface.
3. Unknown individuals trigger the alarm system.
4. Laser security triggers an alarm when interrupted, with all statuses displayed on the website.

## Contributing
Contributions are welcome! Fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License.
