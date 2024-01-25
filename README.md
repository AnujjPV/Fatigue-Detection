Employee Fatigue Detection using OpenCV
Overview
This project utilizes OpenCV, an open-source computer vision library, to implement a fatigue detection system based on facial landmarks. The aim is to accurately determine an employee's fatigue level by analyzing the position of their eyes.

Objectives
Face Detection:

OpenCV is employed to detect the face of an employee using its pre-trained facial detector.
Facial Landmarks:

Utilizing the Dlib library, 68 facial landmarks are identified to map and construct a functional facial structure.
Eye Position Detection:

The system focuses on precise eye position detection to facilitate accurate fatigue level calculations.
Eye Aspect Ratio (EAR):

The EAR is calculated based on facial landmarks to assess fatigue levels.
If the EAR is greater than a predefined threshold, no alert is triggered; otherwise, an alarm sound alerts the employee.
Digital Image Processing
The project involves digital image processing techniques for noise removal, low-level feature extraction, and interpreting object shapes within an image.

OpenCV (Open Computer Vision)
OpenCV, launched in 1999 by Intel, is a C++ library widely used for computer vision tasks. The project has interfaces in C++, Python, Java, and MATLAB.
