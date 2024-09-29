# Eye Tracker Video Analysis using OpenCV and Face Mesh Detection

This project demonstrates an eye-tracking algorithm using OpenCV and the `cvzone` library's Face Detection and Face Mesh modules. The script processes video frames to detect facial landmarks, specifically focusing on the left eye, and identifies the gaze direction (left, right, or center). The iris position is tracked, and the direction is displayed on the video frames.

## Features
- Detects faces and tracks left eye movements.
- Classifies eye gaze direction into "left," "right," or "center."
- Marks the iris on the video feed.
- Saves the processed video with annotations.
- Easy to run with options to output video or display results live.

### Requirements
- Python 3.x
- OpenCV
- cvzone
- NumPy

required packages:
pip install opencv-python numpy cvzone

video_file: The path to the input video file for tracking. Replace "Videos/eye_tracker.mp4" with your desired file path.
output_file: The path where the processed video will be saved. Set to None if no output video is needed. Replace "Videos/output_eye_tracker.avi" as needed.
