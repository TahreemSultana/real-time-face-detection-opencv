# Real-Time Face Detection using OpenCV

A real-time computer vision project that detects human faces from a live webcam feed using Python and OpenCV.

## Project Overview

This project uses OpenCV's Haar Cascade classifier to detect faces in real time. The webcam captures video frames, converts them into grayscale images, and identifies faces using computer vision techniques.

## Features

* Real-time webcam face detection
* Grayscale image processing
* Haar Cascade face detection
* Bounding box around detected faces
* Simple and lightweight implementation

## Technologies Used

* Python
* OpenCV
* Computer Vision
* Haar Cascade Classifier

## How It Works

```text
Webcam
   ↓
Capture Video Frame
   ↓
Convert to Grayscale
   ↓
Face Detection
   ↓
Draw Bounding Boxes
   ↓
Display Result
```

## Project Structure

```text
real-time-face-detection-opencv/
│
├── main.py
├── README.md
└── .gitignore
```

## Installation

Install the required package:

```bash
pip install opencv-python
```

## Run the Project

Run:

```bash
python main.py
```

The webcam window will open automatically.

Press **Q** to stop the program.

## Detection Method

The project uses the pre-trained:

```text
haarcascade_frontalface_default.xml
```

classifier provided by OpenCV for frontal face detection.

## Future Improvements

* Face recognition
* Face tracking
* Multiple object detection
* Real-time face counting
* Integration with deep learning-based detectors

## Author

**Tahreem Sultana**

Artificial Intelligence Student
