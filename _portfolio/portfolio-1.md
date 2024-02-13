---
title: "Oriented Object Detection on Fisheye Security Cameras"
excerpt: "Innovative object detection system using PyTorch, tailored for fisheye security camera datasets. This system is designed to accurately predict oriented bounding boxes, overcoming the unique challenges posed by fisheye lens distortions.<br/><img src='/images/object.png'  style='border: 2px solid #000;'>"
collection: portfolio
---

## Introduction
Fisheye-OBB is a cutting-edge machine learning project focused on the prediction of oriented bounding boxes (OBB) in images captured by fisheye cameras. Utilizing advanced neural network architectures, this project addresses the unique challenges posed by the distortion in fisheye images, making it particularly suited for applications in surveillance, autonomous vehicles, and robotics where wide-angle visual data is prevalent. The project combines innovative approaches in image processing and object detection to deliver accurate and reliable bounding box predictions.

## Table of Contents
- Introduction
- Features
- Model Used
- Visualization Techniques
- Examples
- Contributors

## Features
Fisheye-OBB offers a range of features specifically designed for oriented bounding box detection in fisheye camera images:
- Custom dataset handling tailored for fisheye images.
- Specialized neural network architecture (`RetinaNet` variant) for OBB prediction.
- Comprehensive utility functions for data preprocessing and augmentation.
- Advanced loss functions (`LossFunc`) to optimize OBB prediction.
- Efficient non-maximum suppression (NMS) for bounding box refinement.

## Model Used
The core of Fisheye-OBB is a modified `RetinaNet` model, which has been adapted to handle the unique characteristics of fisheye images. The network utilizes group normalization and custom anchor configurations, making it well-suited for detecting objects with various orientations and sizes in distorted images.

## Visualization Techniques
Visualization plays a crucial role in Fisheye-OBB. The project includes:
- Techniques to visualize the anchor generation process.
- Functions to display predictions overlaying the fisheye images.
- Comparative visualizations to evaluate model performance against ground truth.

## Examples
The project includes Jupyter notebooks (`compare_results.ipynb`, `Training_Notebook.ipynb`, `visualize_anchors.ipynb`) that demonstrate the model training, evaluation, and various visualization techniques.

<img src="\Lunch1_000341.png">
<img src="\Lunch1_001161.png">


## Contributors
Wyatt Mayor

## Project Report

<iframe width="100%" height="900" src="\Project Report.pdf">
