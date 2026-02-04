# Face-EyesDetection

## Real-Time Facial Feature Tracker
This project is a Python-based computer vision tool designed to identify human faces, eyes, and smiles through a live camera feed. It utilizes the OpenCV framework and Haar Cascade algorithms for high-speed object detection.

### Project Components
Face Tracking: Identifies the primary face area and highlights it with a boundary box.

### Ocular Detection: 
Monitors the eye region and provides an on-screen alert when eyes are visible.

Expression Recognition: Scans for smiles and updates the display status accordingly.

### Requirements
To use this software, you need:
Python 3.x environment.
OpenCV Library: Install it via terminal using pip install opencv-python.
Model Files: Ensure the XML classifiers (haarcascade_eye.xml, haarcascade_smile.xml, and haarcascade_frontalface_default.xml) are located in your project directory.

### Usage Instructions
Open your terminal or command prompt.
Navigate to the folder containing Whole_face.py.
Execute the script: python Whole_face.py.
Exit Command: Press the 'a' key to stop the video stream and close the window.

### How it Functions
The application processes video data by converting frames into grayscale to simplify the mathematical analysis. It then isolates the "Region of Interest" (the face) to search for smaller details like eyes and smiles, which makes the detection more efficient.
