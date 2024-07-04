# Face-Recognition-based-Attendance-System
Face Recognition-Based Attendance System Using ESP32-CAM AI Thinker and FTDI Module.
The project involves setting up the hardware, configuring the software, and implementing the system for real-time attendance monitoring.

**Introduction**:
The face recognition-based attendance system leverages the ESP32-CAM AI Thinker module's capabilities to capture and recognize faces, making it an efficient and contactless method for attendance management. The system uses a camera to capture images, processes them to recognize faces, and logs attendance in real-time.

**Components Required**:
ESP32-CAM AI Thinker Module: A low-cost camera module with an integrated ESP32-S chip, capable of capturing images and performing basic image processing.
FTDI Module: A USB-to-Serial adapter used for programming the ESP32-CAM module.
MicroSD Card: Used for storing captured images and other necessary files.
Jumper Wires: For connecting the ESP32-CAM module to the FTDI module.
Breadboard (optional): For organizing connections during setup.
Power Supply: A 5V power supply for the ESP32-CAM module.

**Hardware Setup**:
Connecting ESP32-CAM to FTDI Module:
Connect the GND pin of the ESP32-CAM to the GND pin of the FTDI module.
Connect the VCC pin of the ESP32-CAM to the 3.3V pin of the FTDI module.
Connect the U0R pin of the ESP32-CAM to the TX pin of the FTDI module.
Connect the U0T pin of the ESP32-CAM to the RX pin of the FTDI module.
Connect the GND pin of the ESP32-CAM to the IO0 pin to enable programming mode.

Powering the ESP32-CAM Module:
Ensure the power supply provides a stable 5V output.
Connect the power supply to the 5V and GND pins of the ESP32-CAM module.

Face Detection and Recognition:
The ESP32-CAM module captures images using its onboard camera.
Images are processed to detect faces using the Haar Cascade or other face detection algorithms.
Recognized faces are matched against a pre-trained model or database to identify individuals.

Attendance Logging:
When a face is recognized, the system logs the attendance data (name, date, time) to a file on the MicroSD card or sends it to a server via WiFi.
The attendance log can be accessed and reviewed for record-keeping.

**Conclusion**:
The face recognition-based attendance system using the ESP32-CAM AI Thinker and FTDI module provides an efficient and contactless solution for attendance management. By following the steps outlined in this documentation, you can set up, configure, and implement a reliable attendance system.
