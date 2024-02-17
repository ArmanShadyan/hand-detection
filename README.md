# Real-Time Hand Detection

This project uses the MediaPipe and OpenCV libraries to perform real-time hand detection from a webcam feed.

## Dependencies

- OpenCV
- MediaPipe
- NumPy

You can install these dependencies using pip:

```bash
pip install opencv-python mediapipe numpy


# Usage
To run the script, simply use the following command:
python hand_detection.py
This will open up your webcam and start detecting hands in real-time. Landmarks will be drawn on the detected hands. Press ‘q’ to quit the application.

# How It Works
The script reads frames from the webcam, flips the frame for a selfie-view display, converts the frame to RGB, and processes the frame to find hands. If any hands are detected in the frame, the script draws landmarks on the hands.

# License
This project is licensed under the terms of the MIT License.
