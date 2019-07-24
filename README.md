# Jockey Detection with keras-yolo3 and LeNet

## Introduction

Object detection and classification model built through transfer training on Yolov3 and subsequent classification of detected objects using a neural network with the LeNet architecture.

## Demo

![demo](demo.gif)


## How to use:

SInce this project was developed during my time as an intern at Deloitte, the actual weights that I trained will be kept off the repo, but given the respective weights, run the follow command:
```
python yolo_video.py --model path/to/model --classes_path path/to/class/names --anchors path/to/yolo/anchors --input path/to/input/video
```

## Configs and Tools

1. Tools Used 
    - Python 3.7.2
    - OpenCV 4.1.0
    - Keras 2.2.4
    - Tensorflow 1.14.0


2. Models Used
    - keras-yolo3 by qqwweee (link: https://github.com/qqwweee/keras-yolo3)
    - keras-retinanet 
    - LeNet (implementation by PyImageSearch)

3. Training Tools
    - Google Colab (GPU: Tesla T4/K80)
