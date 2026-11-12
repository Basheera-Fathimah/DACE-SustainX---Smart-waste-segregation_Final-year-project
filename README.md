DACE SustainX 
AI-Powered Smart Waste Segregation and IoT-Based Monitoring System for Sustainable Campus Management

About the Project
DACE SustainX is our final-year Computer Science Engineering project, developed to address the problem of improper waste disposal and waste segregation in campus environments.
We wanted to explore how technologies like Artificial Intelligence and the Internet of Things could be used to make waste management easier and more organised. The system uses an ESP32-CAM to capture images of waste and an AI-based image classification model to identify the waste category. Based on the classification output, a servo motor-based mechanism is designed to direct waste into the appropriate compartment. The project also explores image-based bin monitoring and data logging through the Edge Impulse platform. Our main focus was to build a smart bin prototype that combines image recognition, embedded hardware and waste monitoring in a single system.

Problem Statement
In many educational institutions, organic and non-biodegradable waste is disposed of together. Manual segregation requires additional effort and can expose cleaning staff to unhygienic conditions. Traditional bins also provide no information about their usage or internal status. DACE SustainX explores an automated approach to waste identification and segregation, along with monitoring features that can support better waste management.

Key Features
- AI-based waste image classification.
- Image acquisition using ESP32-CAM.
- Classification into Organic and Non-Biodegradable categories.
- IR sensor-based waste detection at the bin inlet.
- Servo motor-based mechanical sorting mechanism.
- Image-based bin fill-level estimation.
- Classification logging and visualisation through Edge Impulse.
- Edge-based processing using a TinyML model.

Technologies Used
Microcontroller - ESP32-CAM 
Image Processing - Computer Vision 
Machine Learning - Convolutional Neural Network (CNN)
AI Development Platform - Edge Impulse
Development Environment - Arduino IDE 
Hardware Components - IR Sensor, Servo Motor 
Communication - Wi-Fi 

Hardware Components
- ESP32-CAM with OV2640 camera module
- IR sensor
- Servo motor (SG90 / MG996R)
- 5V DC power supply
- Waste bin with separate compartments
- Connecting wires and supporting components

Software Requirements
- Arduino IDE
- Edge Impulse Studio
- Edge Impulse Arduino SDK
- ESP32 board support package

How It Works
The system follows a sequence of image acquisition, classification and waste management operations.

1. Waste Detection
An IR sensor detects the presence of an object at the bin inlet and triggers the image acquisition process.

2. Image Capture
The ESP32-CAM captures an image of the waste item. The captured image is prepared in the required format for classification.

3. AI-Based Classification
The captured image is passed to a CNN-based machine learning model developed using Edge Impulse. The model analyses the image and predicts the corresponding waste category.

4. Waste Segregation Mechanism
The classification result is used to determine the appropriate sorting action. A servo motor-based mechanism is designed to rotate an internal flap and direct the waste into the designated compartment.

5. Monitoring and Data Logging
The ESP32-CAM also supports image-based monitoring of the bin interior. Classification results and related system information can be viewed through the Edge Impulse dashboard.

System Architecture
The project consists of four main functional modules:
1. Image Acquisition Module: Captures waste images using ESP32-CAM.
2. AI Classification Module: Uses a CNN-based model deployed through Edge Impulse.
3. Mechanical Sorting Module: Uses servo motor control for directing waste into separate compartments.
4. Monitoring Module: Supports image-based bin monitoring and classification data visualisation.

Testing
The project report covers testing at both hardware and software levels.
- Unit Testing: Individual testing of camera image capture, servo movement and sensor response.
- Integration Testing: Checking communication between image acquisition, classification and hardware modules.
- Functional Testing: Verifying waste detection, classification and monitoring behaviour.
- White-Box Testing: Checking internal program logic and control flow.
- Black-Box Testing: Observing system behaviour using different inputs and test conditions.

Project Outcomes
The project demonstrates the use of embedded AI and IoT concepts in a practical waste management application.
The developed prototype explores:
- Image-based identification of waste.
- Edge AI classification using ESP32-CAM.
- Hardware-based waste sorting mechanisms.
- Image-based bin monitoring.
- Classification data logging through Edge Impulse.

Future Enhancements
Some possible improvements to the system include:
- Complete integration of the classification model with automatic servo control.
- Support for additional waste categories.
- Improved bin fill-level monitoring.
- Mobile application integration for notifications.
- Predictive waste collection and maintenance.
- Solar-powered operation.

Project Details
Project Name - DACE SustainX 
Project Type - Final Year Project 
Degree - B.E. Computer Science and Engineering 
Institution - Dhaanish Ahmed College of Engineering 
University - Anna University 
Academic Year - 2024–2025 
Domain - Artificial Intelligence, IoT and Embedded Systems 

Team Members
- Basheera Fathimah K F
- Abdullah B
- Abu Kasim S Y

Acknowledgement
This project was completed as part of our Bachelor of Engineering in Computer Science and Engineering at Dhaanish Ahmed College of Engineering.
We are grateful to our project supervisor, faculty members and institution for their guidance and support throughout the project.

DACE SustainX was our attempt to apply what we learned in engineering to a real-world problem. It helped us explore the practical use of AI, embedded systems and IoT in building a smarter approach to waste management.
