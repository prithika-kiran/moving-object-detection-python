# Moving Object Detection using Python & OpenCV

This project implements a real-time moving object detection system using Python, OpenCV, and a live webcam feed. The application captures an initial reference frame and detects motion by comparing incoming frames against it. Moving objects are identified and highlighted using bounding boxes.

This project was built as a learning project by following an OpenCV tutorial to understand computer vision concepts such as frame differencing, contour detection, thresholding, and real-time video processing.

## Features

* Real-time motion detection using laptop webcam
* First-frame background reference method
* Gaussian Blur for noise reduction
* Absolute Difference for frame comparison
* Thresholding and dilation for improved detection
* Contour detection and bounding boxes around moving objects
* Live detection status display
* Press **'q'** to quit the program

## Technologies Used

* Python
* OpenCV (`cv2`)
* imutils
