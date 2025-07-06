# IRDE-DRDO

Project Overview: The system enables autonomous payload drops based on real-time AI object detection and alignment, with full wireless control and precise servo actuation.

📌 Key Features:

📷 Camera Module: Captures real-time visuals (USB Webcam)

🧠 AI Processing: Runs YOLOv8 object detection on the laptop using Python + OpenCV

🎯 Centroid Alignment: Calculates bounding box center to match with drone's frame center

🔄 Servo Motor (SG90): Rotates at precise angles (0° to 180°) to drop 4 payloads sequentially

📡 Bluetooth Module (HC-05): Enables wireless communication between laptop and Arduino

🛩 Microcontroller (Arduino Uno): Controls servo motor based on signals from laptop

📏 Ultrasonic Sensor (HC-SR04): Ensures safe drop height threshold is met before triggering

🖥 CAD Design: Entire drop mechanism and payload holder designed using SolidWorks

💻 Laptop: Performs image processing and decision-making using Python

