# Eye Tracker Video Analysis using OpenCV and Face Mesh Detection

## Overview

This project demonstrates an eye-tracking algorithm using OpenCV and the `cvzone` library's Face Detection and Face Mesh modules. The script processes video frames to detect facial landmarks, specifically focusing on the left eye, and identifies the gaze direction (left, right, or center). The iris position is tracked, and the direction is displayed on the video frames.

## Features
- Detects faces and tracks left eye movements.
- Classifies eye gaze direction into "left," "right," or "center."
- Marks the iris on the video feed.
- Saves the processed video with annotations.
- Easy to run with options to output video or display results live.

## Installation

### Requirements
- Python 3.x
- OpenCV
- cvzone
- NumPy

To install the required packages, run:

```bash
pip install opencv-python numpy cvzone



Here’s a suggested title, description, and README content for your GitHub repository:

Repository Title:
Eye Tracker Video Analysis using OpenCV and Face Mesh Detection

Description:
This repository contains a Python script for eye tracking using OpenCV and the cvzone Face Mesh Detection module. The script processes video files to detect the position of a person's left eye and tracks the iris movements to classify gaze direction as "left," "right," or "center." It also supports saving the processed video output.

README.md:
md
Copy code
# Eye Tracker Video Analysis using OpenCV and Face Mesh Detection

## Overview

This project demonstrates an eye-tracking algorithm using OpenCV and the `cvzone` library's Face Detection and Face Mesh modules. The script processes video frames to detect facial landmarks, specifically focusing on the left eye, and identifies the gaze direction (left, right, or center). The iris position is tracked, and the direction is displayed on the video frames.

## Features
- Detects faces and tracks left eye movements.
- Classifies eye gaze direction into "left," "right," or "center."
- Marks the iris on the video feed.
- Saves the processed video with annotations.
- Easy to run with options to output video or display results live.

## Installation

### Requirements
- Python 3.x
- OpenCV
- cvzone
- NumPy

To install the required packages, run:

```bash
pip install opencv-python numpy cvzone
Usage
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/eye-tracker-video.git
Navigate to the project directory:

bash
Copy code
cd eye-tracker-video
Run the script:


video_file: The path to the input video file for tracking. Replace "Videos/eye_tracker.mp4" with your desired file path.
output_file: The path where the processed video will be saved. Set to None if no output video is needed. Replace "Videos/output_eye_tracker.avi" as needed.
