GuardianDrive - Safe Journey Assurance System

Overview

GuardianDrive is an embedded project focused on ensuring a safe journey for drivers and passengers by actively monitoring various safety parameters during a vehicle journey. The system integrates a range of sensors, including gas sensor (alcohol detection), vibration sensor (accident detection), and infrared sensor (seat belt detection) to implement comprehensive safety measures. In case of potential hazards, the system takes appropriate actions, such as preventing the vehicle from starting or sending an alert with the location information.


![image](https://github.com/venkatesh182002/Safe_Journey_Assurance_System/assets/74310227/1c62d395-e85b-421b-8445-5ac84cebb438)


Key Features

Alcohol Detection: The gas sensor is utilized to detect alcohol levels in the driver's breath. If alcohol is detected, the system prevents the vehicle from starting, ensuring a responsible and safe driving experience.

Seat Belt Detection: The infrared sensor monitors the presence of a seat belt. If the seat belt is not detected, the system prevents the vehicle from starting until the seat belt is fastened.

Accident Detection: The vibration sensor is used to detect accidents or collisions. In the event of an accident, the system immediately sends a distress message containing location information to predefined emergency contacts via a GSM module.

GPS Location Reporting: The system includes a GPS module to obtain accurate location data. In case of an accident, the system uses this information to notify emergency contacts with the precise location.


Hardware Components

Gas Sensor (Alcohol Detection)

Vibration Sensor (Accident Detection)

Infrared Sensor (Seat Belt Detection)

Relay (Motor Control)

Buzzer (Accident Alert)

GPS Module (Location Tracking)

GSM Module (Message Sending)


Software Components

Arduino IDE for writing and uploading the code to the embedded board.

Proteus for simulation and testing of the embedded system.


Installation and Usage

Clone this repository to your local machine.

Open the Arduino IDE and upload the code to the embedded board used in the project.

Set up the Proteus simulation with the appropriate sensor input signals and verify the system's behavior.

Connect the hardware components as per the circuit diagram provided in the repository.

Power up the system and observe the LCD display for status messages.

Test the system with different scenarios, such as alcohol detection, seat belt detection, and accident simulation, to ensure its proper functioning.


Future Enhancements

Implement real-time communication between the system and a mobile app for receiving live updates and notifications.

Integrate advanced driver assistance features, such as lane departure warnings and collision avoidance.

Enhance the accuracy of alcohol detection by using more sophisticated gas sensors.


Contribution

Contributions to this project are welcome. If you find any issues or have ideas for improvement, feel free to open an issue or submit a pull request.


Acknowledgments

TinyGPS library for GPS functionality.

LiquidCrystal library for interfacing with the LCD display.

Arduino community for valuable resources and inspiration.


Disclaimer

GuardianDrive is an academic and hobbyist project intended for educational purposes. While efforts have been made to ensure its accuracy and reliability, it should not be used as a substitute for professional-grade safety systems in real-world scenarios. The developers and contributors are not liable for any potential damages or risks arising from the usage of this project. Always prioritize the use of certified safety systems and comply with local traffic laws and regulations.
