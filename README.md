# Real-time Object Detection with YOLO and Webcam

This project implements real-time object detection using YOLOv3 (You Only Look Once) and a webcam feed, built with Python and OpenCV. It detects objects from 80 different classes defined in the COCO dataset and displays bounding boxes with labels and confidence scores.

## Features
- Real-time object detection using webcam feed
- Detects 80 different object classes from the COCO dataset
- Displays bounding boxes with class labels and confidence scores
- Uses YOLOv3 pre-trained model

## Prerequisites

Before running the project, ensure you have the following:

### Software Requirements
- Python 3.6+
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

### Required Files
1. `yolov3.weights` - Pre-trained weights file (~237MB)
2. `yolov3.cfg` - YOLO configuration file
3. `coco.names` - File containing 80 class names

Download these files:
- [yolov3.weights](https://pjreddie.com/media/files/yolov3.weights)
- [yolov3.cfg](https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg)
- [coco.names](https://github.com/pjreddie/darknet/blob/master/data/coco.names)

Place all downloaded files in the same directory as the Python script.

## Installation

1. Clone this repository:
```bash
git clone <repository-url>
cd <repository-name>
