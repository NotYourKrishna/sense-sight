# Sense-Sight: Real-Time Object Detection with Audio Feedback

## Overview

Sense-Sight is an AI-based system designed to assist visually impaired users by detecting objects in real-time and providing audio feedback.


## Features

* Real-time object detection using YOLO
* Audio feedback using text-to-speech (pyttsx3)
* Customizable object detection list
* Works offline


## Requirements

* Python 3.x
* Webcam


## Setup Instructions

### 1. Clone the Repository

git clone https://github.com/NotYourKrishna/sense-sight
cd sense-sight

### 2. Install Dependencies

pip install -r requirements.txt

### 3. Download YOLO Weights

Download yolov3.weights from:
https://pjreddie.com/darknet/yolo/

Place it in the project folder.

### 4. Configure Target Objects

Edit file:
target_objects.txt

Example:
person
dog
laptop

### 5. Run the Project

python main.py

Press 'q' to exit.


## How It Works

* Webcam captures live video
* YOLO detects objects
* If object is in target list → audio alert



## Notes

* Ensure webcam is connected
* Works best in good lighting


---

## Author

Krishna (23BAI10621)

