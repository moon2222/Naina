# Naina

## Table of Contents
Introduction
Features
System Requirements
Installation
Usage
Configuration
Supported Cameras
Contributing
License
Contact

## Introduction
Welcome to Naina for Streaming and Recording! This application provides a powerful and user-friendly interface for live streaming and recording video from various sources, including IP cameras, local webcams, RTSP streams, and USB cameras. Whether you're building a home security system or conducting video surveillance for your business, this application has you covered.

## Features
Live streaming of video from IP cameras, local webcams, RTSP streams, and USB cameras.
Recording of live streams with customizable storage options.
Support for multiple camera sources simultaneously.
Real-time video preview with adjustable video quality.
Motion detection and alerts for security monitoring.
Web-based interface for easy access from any device with a web browser.
User authentication and access control for secure usage.
System Requirements
Before installing and using this application, ensure that your system meets the following requirements:

Operating System: Windows, macOS, or Linux
Web Browser: Google Chrome, Mozilla Firefox, Microsoft Edge, or Safari
Processor: Dual-core 1.6 GHz or higher
RAM: 4 GB or more
Disk Space: 200 MB for application installation
Network: Stable internet connection for remote access
Installation
To install the Web Server Application, follow these steps:

Clone this repository to your local machine.
Install the required dependencies by running the following command:
Copy code
npm install
Configure the application settings (see Configuration section).
Start the application by running:
sql
Copy code
npm start
Access the application through your web browser using the provided URL.
Usage
Once the application is up and running, follow these steps to use it:

Login to the application using your credentials.
Click on "Add Camera" to configure and add your camera source (IP camera, webcam, RTSP stream, or USB camera).
Configure the camera settings, such as resolution, frame rate, and recording options.
Save the camera configuration.
Click on the camera thumbnail to view the live stream or recording.
Use the playback controls to view past recordings, if enabled.
Monitor the live streams and recordings from the application's dashboard.
Configuration
To configure the application, navigate to the config folder and modify the following files:

config.js: Set general application settings, such as the server port, storage directory, and authentication settings.
cameras.json: Add camera configurations, including camera type, IP address, port, username, password, etc.
Supported Cameras
The Web Server Application supports the following camera sources:

IP Cameras (RTSP, HTTP/HTTPS)
Local Webcams
RTSP Streams
USB Cameras
Contributing
We welcome contributions to this project! If you find any bugs or have feature requests, please open an issue in the GitHub repository. If you'd like to contribute code, create a pull request, and we'll review it as soon as possible.

License
shashank

Contact
If you have any questions or need further assistance, please feel free to contact our support team at shashankmishra2222@gmail..com. We'd be happy to help!
