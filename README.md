# 🦷 Dental Cavity Detection using YOLOv8

## Overview

This project presents an AI-based system for detecting dental cavities from X-ray images using deep learning and object detection.

## Problem Statement

Detecting dental cavities manually can be difficult and time-consuming, especially in early stages. This system helps automate the detection process and improves diagnostic accuracy.

## Solution

A YOLOv8-based object detection model is trained on a custom dataset of dental X-ray images to identify cavity regions with high precision.

---

## Model Details

* Model: YOLOv8 (Medium & Large)
* Framework: PyTorch (Ultralytics)
* Task: Object Detection
* Image Size: 640
* Epochs: 150
* Accuracy: ~96% mAP

---

## Dataset

* Custom dataset created using Roboflow
* Annotated dental X-ray images
* Data augmentation applied (mosaic, mixup, flipping, HSV)

---

## Training Configuration

* Batch Size: 14
* Learning Rate: 0.00029
* Momentum: 0.89
* Weight Decay: 0.00087

---

## Inference

The trained model detects cavities in X-ray images and highlights affected regions using bounding boxes.

---

## Future Work

* Improve detection of small cavities
* Deploy as a web application
* Real-time dental analysis system

---

## Author

Esa Khan
AI Engineer 
