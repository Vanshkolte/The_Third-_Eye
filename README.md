## The Third Eye - An Assistive Technology for the Blind & Visually Impaired Individuals
The Third Eye is an assistive technology project designed to help blind and visually impaired individuals navigate their surroundings with increased safety. The device uses ultrasonic sensors to detect obstacles and alert the user through a buzzer, providing real-time feedback on potential hazards.

### Components Used
Arduino Nano: The microcontroller used to process sensor data and control outputs.
Buzzer: Provides audio feedback to alert the user when an obstacle is detected.
Ultrasonic Sensor: Detects obstacles in the path of the user by measuring the distance to objects.
9V Battery: Powers the entire system.
Battery Clip: Connects the 9V battery to the Arduino Nano.
Push Button: Allows the user to manually reset the system or trigger specific functions.
Glasses: The frame to which all components are mounted, worn by the user.
Jumper Wires: Connects all components, enabling communication between the Arduino Nano and the sensors/buzzer.
### Software
Arduino IDE: The development environment used to write, compile, and upload code to the Arduino Nano.
How It Works
The ultrasonic sensor continuously emits sound waves and listens for their echoes. When an obstacle is detected within a certain range, the Arduino Nano processes the data.
If an obstacle is detected within a pre-set distance, the Arduino Nano triggers the buzzer, providing an audible alert to the user.
The user can adjust or reset the device using the push button, allowing for easy control and customization.
Setup Instructions
### Hardware Assembly:

Mount the ultrasonic sensor and buzzer on the glasses.
Connect the components to the Arduino Nano using jumper wires.
Power the system using the 9V battery and battery clip.
Software Installation:

### Install the Arduino IDE on your computer.
Download the code from this repository.
Open the code in the Arduino IDE and upload it to the Arduino Nano.
Operation:

Power on the device by connecting the 9V battery.
Wear the glasses, ensuring the ultrasonic sensor faces forward.
The device will automatically start detecting obstacles and provide audio feedback through the buzzer.
Project Status
This project is currently in development. Contributions and suggestions are welcome!

### Contributing
If you would like to contribute to this project, please fork the repository and create a pull request with your improvements.

### License
This project is licensed under the MIT License. See the LICENSE file for more details.

