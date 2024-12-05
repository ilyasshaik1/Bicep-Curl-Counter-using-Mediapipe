# Bicep Curl Counter using Mediapipe

This project is a real-time bicep curl counter application built using Python, OpenCV, and Mediapipe. The application tracks the user's arm movements using the webcam, calculates the angle at the elbow, and counts repetitions of bicep curls based on the angle.

## Features

- Real-time bicep curl counting.
- Displays the number of repetitions and the stage ("up" or "down").
- Visualizes the pose landmarks and the angle of the elbow.
- Tracks only the left arm (can be extended for both arms).
- Provides a user-friendly interface with real-time feedback.

## Requirements

To run this project, you'll need the following Python packages:

- `opencv-python` for computer vision and webcam capture.
- `mediapipe` for pose detection and human landmark tracking.
- `numpy` for numerical operations (used to calculate angles).

You can install these dependencies using `pip`:

```bash
pip install opencv-python mediapipe numpy
