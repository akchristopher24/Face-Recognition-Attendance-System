Face Recognition System
Overview
This repository contains a Python script that implements a real-time face recognition system using OpenCV and face_recognition libraries. The system is designed to recognize faces in a video feed and log the names and timestamps to a CSV file.
Features
Real-time face recognition using OpenCV and face_recognition libraries
Face encoding and comparison for accurate recognition
Logging of recognized names and timestamps to a CSV file
Ability to add new faces to the recognition system by adding images to the Training_images directory
Requirements
Python 3.11
OpenCV (cv2) library
face_recognition library
numpy library
Installation
Clone the repository to your local machine.
Install the required libraries using pip: pip install opencv-python face_recognition numpy
Add images of the faces you want to recognize to the Training_images directory.
Usage
Run the script using Python: python face_recognition.py
The system will start recognizing faces in the video feed and logging the names and timestamps to register.csv
Directory Structure
Training_images: Directory containing images of faces to be recognized
face_recognition.py: Main script for face recognition
register.csv: CSV file for logging recognized names and timestamps
Contributing
Contributions are welcome! If you'd like to add new features or improve the system, please submit a pull request.
