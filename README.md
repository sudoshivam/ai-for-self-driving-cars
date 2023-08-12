# Semantic Segmentation and Object Detection for Self-Driving Cars

This repository showcases the implementation of both **Semantic Segmentation Model** and **Object Detection Model** for Self-Driving Cars.
## Introduction

Semantic segmentation and object detection are critical tasks for enabling self-driving cars to perceive and navigate their surroundings safely.

### Semantic Segmentation

Semantic segmentation involves labeling each pixel in an image with its corresponding object class. This detailed understanding of the road scene aids in safe navigation and decision-making.

### Object Detection
Object detection is a fundamental computer vision task that involves identifying and locating objects of interest within an image. For self-driving cars, object detection helps in identifying various obstacles, pedestrians, other vehicles, and road signs in the environment.

## U-Net Architecture for Semantic Segmentation

The U-Net architecture is employed for semantic segmentation due to its effectiveness in capturing spatial information. It features a contracting path for context extraction and an expansive path for accurate segmentation.

## YOLOv3 Architecture for 2D Object Detection

YOLOv3 is utilized for object detection due to its speed and accuracy. It divides an image into a grid and predicts bounding boxes and class probabilities for objects in each grid cell.

## Dataset

The project utilizes the 'Lyft Udacity Challenge for Self Driving Cars' datasets, available on Kaggle:
- For semantic segmentation - ([Semantic Segmentation for Self Driving Cars | Kaggle](https://www.kaggle.com/datasets/kumaresanmanickavelu/lyft-udacity-challenge)).
- For object detection - ([Lyft 3D Object Detection for Autonomous Vehicles | Kaggle](https://www.kaggle.com/competitions/3d-object-detection-for-autonomous-vehicles)).

## Results

### U-Net Semantic Segmentation
- Training accuracy: 98.02%
- Validation accuracy: 97.78%
- Sample Segmentation Results:
  ![Sample Segmentation Result 1](/prediction/1.png)
  ![Sample Segmentation Result 2](/prediction/2.png)

### YOLOv3 Object Detection
- Sample Object Detection Results:
  ![Sample Object Detection Result 1](/prediction/yolov3.png)

The `code` folder contains model codes. Feel free to explore more results and the model's performance in the project's Jupyter Notebook.
