# Gods_eye
 A resnet-34 and tessaract-ocr based surveillance system with the future scope for GAIT analysis.\
 Research paper associated with it - https://www.academia.edu/71155770/Smart_Surveillance_and_Tracking_System_using_Resnet_and_Tesseract_OCR

# Smart Surveillance and Tracking System

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [System Architecture](#system-architecture)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset and Models](#dataset-and-models)
- [Results](#results)
- [Future Scope](#future-scope)
- [Contributors](#contributors)

---

## Overview

The **Smart Surveillance and Tracking System** is a multi-camera security solution designed to enhance surveillance in large-scale environments such as offices, banks, shopping malls, and residential areas. It utilizes advanced computer vision techniques for:
1. **Face Recognition** using ResNet-34.
2. **Vehicle Number Plate Recognition** using Tesseract OCR.

The system tracks individuals and vehicles across multiple cameras, mapping their movements with timestamps and locations for real-time monitoring.

---

## Features
- **Face Recognition**: Detects and identifies individuals using ResNet-34 and KNN classification.
- **Vehicle Number Plate Recognition**: Extracts and identifies license plate numbers using Tesseract OCR.
- **Multi-Camera Integration**: Processes video feeds from multiple IP-enabled cameras.
- **Real-Time Tracking**: Maps detected persons or vehicles on a graphical interface with timestamps.
- **Scalable Design**: Easily extendable by adding more cameras to the network.

---

## System Architecture

The system consists of:
1. **IP Cameras**: Captures video feeds from monitored areas.
2. **Centralized Processing Unit**:
   - Face recognition using ResNet-34.
   - Vehicle number plate recognition using Tesseract OCR.
3. **Database**: Stores detection data (timestamps, locations).
4. **Tracking Module**: Visualizes movement on a map.

---

## Technologies Used
### Frameworks and Libraries
- **Python**
  - OpenCV (video processing)
  - TensorFlow/PyTorch (ResNet implementation)
  - Tesseract OCR
  - NumPy, Pandas (data handling)

### Models
- ResNet-34 for face recognition.
- Tesseract OCR for vehicle number plate recognition.

### Tools
- IP-enabled cameras.
- Database management system (e.g., MySQL or SQLite).

---

## Installation

1. Clone the repository:
git clone https://github.com/your-repo/smart-surveillance-system.git
cd smart-surveillance-system

2. Install dependencies:
pip install -r requirements.txt

---

## Usage

1. Launch the system and ensure all connected cameras are operational.
2. Input details of the person or vehicle to track (e.g., face image or license plate number).
3. View real-time detections and tracking on the graphical interface.

---

## Dataset and Models

### Face Recognition
- **Dataset**: Labeled Faces in the Wild (LFW).
- Subset used: 9,000+ images of 1,680 individuals.
- Accuracy achieved: **92.35%**.

### Vehicle Number Plate Recognition
- **Dataset**: Car License Plate Detection dataset.
- Distinct images: 433 license plates.
- Accuracy achieved with Tesseract OCR: **95.62%**.

---

## Results

| Feature                      | Methodology          | Accuracy    |
|------------------------------|----------------------|-------------|
| Face Recognition             | ResNet-34 + KNN     | 92.35%      |
| Vehicle Number Plate Detection | Tesseract OCR       | 95.62%      |

---

## Future Scope

1. Enhance model robustness under varying lighting and weather conditions.
2. Address blind spots in multi-camera setups by optimizing camera placement.
3. Integrate additional features like behavior analysis or anomaly detection.
4. Improve scalability for larger networks with hundreds of cameras.

---

## Contributors

This project was developed by students from Pune Institute of Computer Technology:

1. Chaitanya Sonavane  
Email: csonawanecs7299@gmail.com  
2. Piyush Kulkarni  
Email: piyush140899@gmail.com  
3. Omkar Podey  
Email: omkarpodey@gmail.com  
4. Pranay Rewane  
Email: rewanepranay@gmail.com  

Special thanks to Prof. B.A. Sonkamble and Asst. Prof. R.A. Kulkarni for their guidance.

--- 

Feel free to contribute to this project by submitting issues or pull requests!
