# Fisheye Camera Calibration Using OpenCV
The application is OpenCV's default code for fisheye camera calibration.

## Dependencies
* OpenCV 3.x.x
* C++11 or C++0x Compiler
* pkg-config

## Installation
```git clone https://github.com/sakshamgupta006/fisheye_calibration.git
cd fisheye_calibration
g++ camera.cpp `pkg-config --libs opencv` -o camera
```

This will create a binary file named "camera".

# Running	
Put all the calibration pictures in a folder.
