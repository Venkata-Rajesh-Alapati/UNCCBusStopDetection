## Name
UNCC Bus Stop detection

## Description
The UNCC Bus Stop Detection project is an automated system that utilizes object detection and optical character recognition (OCR) to detect and identify bus stops in a video stream. The system consists of two classes of objects, namely "Bus stop shelter" and "Bus stop sign board". The yolov7 model is used for detecting these objects, which allows for accurate detection of both the bus stop sign board and the shelter.

Once the bus stop sign board is detected, the system crops the image and applies preprocessing techniques to enhance the image quality. This is followed by performing OCR to extract the bus stop number from the sign board. The system then tracks the occurrence of bus stop numbers in each frame of the video, and the bus stop that appears most frequently is identified as the bus stop in the input video.

## Badges
![Object Detection](https://img.shields.io/badge/Object%20Detection-Passing-brightgreen)

![OCR](https://img.shields.io/badge/OCR-Passing-brightgreen)

## Visuals
Click the image below to watch the demo video.

[![Demo Video](https://img.youtube.com/vi/SoGs2Rjn1NI/0.jpg)](https://www.youtube.com/watch?v=SoGs2Rjn1NI)

## Installation
Before installing the UNCC Bus Stop Detection project, make sure you have the following requirements:

Python 3.6 or higher

OpenCV

Here are the steps to install the project:

1. Download the yolov7 directory from the following link: https://drive.google.com/drive/folders/1yuvW6BhIrJRHmDtTcW5uAgUTTG9EYAP_?usp=sharing

2. Download the TrainYOLOv7.ipynb notebook file.

3. Open the TrainYOLOv7.ipynb file and change any directory paths that need to be updated to match your system.

## Usage
To use this Bus Stop Detection system, follow these steps:

1. Pass the link for the input video to detect to the 'input_path' variable in the TrainYOLOv7.ipynb notebook.
2. Restart the kernel and run all the cells.
3. The results will be stored in the yolov7/runs/detect/exp directory.

## Support
If you encounter any issues or have questions, contact me via email at valapati@uncc.edu

## Authors and acknowledgment
We would like to thank the developers of YOLOv7 for their excellent work in developing this object detection algorithm. Their contributions have made it possible for us to build on top of their work and create this project.

## Project status
Please note that the project was developed within the scope and requirements of the 'ITCS-5152 Computer Vision' and may not be actively maintained or updated beyond the end of the course.
