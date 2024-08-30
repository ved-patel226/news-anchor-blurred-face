# README

## Overview
This project captures video from your webcam, detects faces using MediaPipe, and streams the processed video through a virtual camera using `pyvirtualcam`. The script blurs all but the largest detected face. Use obs virtual cam to record.

## Requirements
- Python 3.x
- OpenCV
- MediaPipe
- PyVirtualCam
- Termcolor

## Installation
1. Install Python 3.x from [python.org](https://www.python.org/downloads/).
2. Install the required packages using pip:
   ```bash
   pip install opencv-python mediapipe pyvirtualcam termcolor
