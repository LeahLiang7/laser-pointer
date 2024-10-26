This project demonstrates a Python application that detects a laser pointer’s red dot through a webcam feed. The program identifies the laser pointer up to a distance of 2 meters with a tolerance of 10 cm. Using OpenCV, it captures video frames, filters red color in HSV color space, and highlights the laser point in real-time.

Features:
1.Real-Time Detection: Continuously monitors the webcam feed for the red laser dot.
2.Color Filtering: Uses HSV color space to isolate the laser pointer’s red color, improving accuracy.
3.Contour Detection: Identifies the laser dot’s position by drawing a circle around it.
4.Distance Tolerance: Configured to detect the laser point up to a specified distance with a defined tolerance.

Technologies Used:
Python 
OpenCV for image processing
NumPy for matrix operations

Installation Requirements:
Install the required libraries (opencv-python, numpy)
Connect a camera to the computer or Raspberry Pi for real-time video feed processing.
