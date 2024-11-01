# Drowsiness Detection System

This project aims to detect drowsiness in real-time using facial landmarks and a deep learning model. The system uses MediaPipe for face landmark detection and OpenCV for face detection, providing alerts if signs of drowsiness are detected.

## Features
- **Real-Time Detection**: Continuously monitors the driver's eye status to detect drowsiness.
- **Deep Learning Model**: A Convolutional Neural Network (CNN) model classifies drowsy and alert states based on eye landmarks.
- **Alerts**: Generates alerts when drowsiness is detected to improve safety.

## Setup and Installation

### Requirements
- Python 3.8+
- Required libraries:
    ```bash
    pip install mediapipe opencv-python-headless tensorflow numpy matplotlib
    ```

### Files Structure
```plaintext
.
├── data/
│   ├── Fatigue Subjects/
│   └── Active Subjects/
├── models/
│   └── drowsiness_model.h5
├── src/
│   ├── drowsiness_detection.py
│   ├── preprocess_data.py
│   └── utils.py
├── README.md
└── requirements.txt
