AI Virtual Mouse Using Hand Gestures

Overview

An AI-based virtual mouse developed as my final-year project for my BS in Information Technology. The application uses computer vision and hand tracking to control mouse movements and clicks through hand gestures, reducing the need for a physical mouse.

Technologies Used

Python — application logic

OpenCV — webcam input and image processing

MediaPipe — real-time hand landmark detection

PyAutoGUI — mouse cursor movement and clicking

How It Works

Captures live video through a webcam.

Processes video frames using OpenCV.

Detects hand landmarks using MediaPipe.

Maps hand landmark coordinates to screen coordinates to move the cursor.

Uses the distance between selected hand landmarks to trigger a mouse click.

My Contribution

I developed this project individually, integrating hand tracking, coordinate mapping, and mouse automation using Python libraries.

Learning Outcomes

Practical experience with Python and computer vision.

Understanding of hand landmark detection and coordinate mapping.

Integration of computer vision with desktop automation.

Project Status

Developed as an academic prototype. Further improvements could include smoother cursor movement, configurable gesture controls, and more robust error handling.

Setup

Install Python and the required libraries:

pip install opencv-python mediapipe pyautogui

Run the Python script:

python "ai mouse.py"

A working webcam and appropriate screen permissions are required. Library versions may need adjustment depending on the Python environment.

Note

This project demonstrates my academic work and learning in computer vision. It was not deployed as a production system.
