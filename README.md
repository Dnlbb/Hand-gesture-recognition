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

## Project Structure

- **hand_gesture_recognition.py**: The main script that initializes the hand landmark detection and gesture recognition.

## Dataset

The dataset consists of JSON formatted files containing hand landmarks and corresponding labels. Each entry includes:

- `landmarks`: Hand landmarks captured as x, y coordinates.
- `labels`: Gesture labels corresponding to the landmarks.
- `leading_hand`: Indicates the primary hand (left or right).

## Model Training

The Random Forest model is trained on a subset of pre-processed hand landmark data. The model is serialized and can be loaded to make predictions in real-time.
