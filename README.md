# Hand Tracking + Gesture + Volume Control

This project is a real-time computer vision system using MediaPipe and OpenCV for hand tracking, gesture recognition, and system volume control.

## Features

- Real-time hand tracking using MediaPipe (21 landmarks)
- Detection of left and right hands
- Gesture recognition:
  - Open Palm
  - Peace
  - Fist
- Volume control using distance between thumb and index finger
- FPS counter for performance monitoring

## How It Works

The system uses MediaPipe Hand Landmarker to detect 21 key points on each hand.

- Hand landmarks are extracted from webcam input
- Left hand is used for gesture recognition
- Right hand is used for volume control
- Distance between thumb and index finger is mapped to system volume

## Requirements

Install dependencies using:
pip install opencv-python mediapipe numpy pycaw comtypes

## Run Project

Run the main script:
python main.py
Make sure your webcam is connected.

## Controls

- Thumb + Index finger distance controls system volume
- Left hand gestures:
  - Open Palm
  - Peace sign
  - Fist

## Notes

- Good lighting improves accuracy
- Hand orientation may affect left/right detection
- MediaPipe may occasionally swap hand labels depending on angle

## Future Improvements

- Add volume bar UI
- Add gesture-based media control
- Improve gesture accuracy
- Convert code into modular structure

## Author

This project was created as a computer vision learning project using Python, OpenCV, and MediaPipe.
