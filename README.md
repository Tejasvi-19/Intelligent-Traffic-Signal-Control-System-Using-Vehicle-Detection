# Intelligent Traffic Signal Control System Using Vehicle Detection

##  Project Overview

The Intelligent Traffic Signal Control System uses Artificial Intelligence, Computer Vision, and YOLOv8 to detect vehicles, estimate traffic density, and dynamically control traffic signals.
Unlike traditional fixed-time traffic signals, the proposed system adapts signal timing according to the real-time number of vehicles in each lane.

##  Objectives

- Detect vehicles in different traffic lanes.
- Estimate traffic density based on vehicle count.
- Dynamically assign green signal timing.
- Detect and prioritize emergency vehicles.
- Reduce unnecessary waiting time and traffic congestion.
- Improve traffic flow at intersections.

##  Technologies Used

- Python
- YOLOv8
- OpenCV
- Computer Vision
- Deep Learning
- COCO Dataset
- Custom Emergency Vehicle Dataset

##  System Workflow

1. Capture traffic images from different lanes.
2. Preprocess the images.
3. Detect vehicles using YOLOv8.
4. Count vehicles in each lane.
5. Estimate traffic density.
6. Detect emergency vehicles.
7. Give priority to emergency vehicles.
8. Select the lane with the highest traffic density.
9. Dynamically control the traffic signal.
10. Display vehicle detection and signal status.

##  Emergency Vehicle Priority

When an emergency vehicle such as an ambulance is detected, the system gives priority to that lane and assigns the green signal to allow the emergency vehicle to pass quickly.

##  Results

The system successfully detects vehicles and emergency vehicles using YOLOv8 and dynamically controls traffic signals based on vehicle density.
The emergency vehicle detection model achieved high precision, recall, and mAP values during evaluation.

##  Project Files

- `trafficf2.py` — Main Python implementation
- `lane1.jpg` — Lane 1 input image
- `lane2.jpg` — Lane 2 input image
- `lane3.jpg` — Lane 3 input image
- `lane4.jpg` — Lane 4 input image

##  Future Scope

- Real-time CCTV/video stream integration
- Multiple intersection coordination
- Improved emergency vehicle detection
- IoT-based traffic signal hardware integration
- Deployment in real-world smart city environments
