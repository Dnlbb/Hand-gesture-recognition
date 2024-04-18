# Hand Gesture Recognition System

This project demonstrates a hand gesture recognition system that uses a Random Forest classifier to detect and classify hand gestures as "like" or "not like". The system employs the MediaPipe framework to detect hand landmarks from live video feed, and these landmarks are used as features for machine learning.

## Features

- Hand landmark detection using MediaPipe.
- Hand gesture classification using a trained Random Forest model.
- Real-time gesture recognition from webcam video stream.

## Requirements

- Python 3.6+
- OpenCV
- MediaPipe
- NumPy
- scikit-learn

## Installation

To run this project, you need to install the required Python libraries. You can install these packages using pip:

```bash
pip install opencv-python-headless mediapipe numpy scikit-learn
