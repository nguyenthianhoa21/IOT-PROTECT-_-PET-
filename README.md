# IOT-PROTECT PET 
# Project Title: PETCARE - Pet Health Monitoring and Location Tracking Device
# Overview
PETCARE is a comprehensive IoT solution designed to monitor the health and track the location of pets. Developed by Team 16 as a part of their end-of-course project in Physics for Information Technology at the University of Science, Ho Chi Minh City, this project integrates a variety of technologies to ensure the well-being and safety of pets.

Features
Temperature Monitoring: PETCARE allows pet owners to monitor their pet's temperature in real-time via a web interface. Alerts are sent to the user if the pet's temperature deviates from the normal range.
GPS Location Tracking: The device provides accurate GPS tracking of the pet's location, viewable on the web interface. The GPS functionality ensures that pet owners can always find their pets if they go astray.
Wi-Fi Connectivity: The device utilizes an ESP32 on Wokwi for seamless internet connectivity, enabling the transmission of temperature and GPS data to the web interface and the reception of commands from the user.
Cloud Integration: User and pet data are securely stored and managed in the cloud using Firebase, ensuring data availability and integrity.
Alerts and Notifications: Users receive notifications via email if their pet's temperature is abnormal. Additionally, the device can send signals to activate an LED light and a ringing bell to locate the pet when needed.
Product Design
3D Design: PETCARE is designed with a focus on comfort and convenience. The device includes features like an adjustable collar, temperature sensors, LED lights, and a ringing bell.
Data Transmission: The device communicates with the web interface, sending pet temperature and GPS data, and receiving commands for the LED light and ringing bell.
User Interface: The web interface provides functionalities for user login, registration, password recovery, and user data management. It also displays the pet's temperature and location data and allows users to send commands to the device.
Web Functionalities
Login/Registration: Users can create an account, log in, and recover forgotten passwords.
Home Page: After login, users are directed to the home page where they can navigate to pet information or user settings.
Pet Page: This page displays the pet's temperature and GPS data. It also allows users to activate the LED light and ringing bell on the pet's device.
User Page: Users can view and edit their login credentials and pet information. They can also navigate back to the home page from here.
Technical Specifications
Required Libraries for Device Operation:
DHT sensor library for ESPx
PubSubClient
TinyGPSPlus-ESP32
Required Templates for Web Operation:
node-red-contrib-firebase
node-red-contrib-web-worldmap
node-red-dashboard
node-red-node-email
Installation & Setup
Importing Code to Node-Red: Users must input their email credentials in the UserID and password fields in the Node email for the code to function correctly.
Email Configuration: Due to privacy and security reasons, users are advised to set up their email configuration as per the instructions provided.
Developers
Trịnh Hoàng An | 21127577
Lâm Thiều Huy | 21127056
Acknowledgements
The team extends their gratitude to ThS. Cao Xuân Nam and ThS. Đặng Hoài Thương for their guidance and support throughout the project.

For detailed information about the project design, functionalities, and implementation, please refer to the project report.
