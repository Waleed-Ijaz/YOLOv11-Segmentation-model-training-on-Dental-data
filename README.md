# YOLOv11 Dental Segmentation
A computer vision project for dental image segmentation using YOLOv11 instance segmentation model. This project trains a custom YOLOv11 model to identify and segment dental structures in medical images.
Project Overview
This project implements dental image segmentation using the latest YOLOv11 architecture. The model is trained on a custom dental dataset with preprocessing techniques to improve model performance and generalization.
Dataset

## Source: Custom dental dataset hosted on Roboflow
Type: Instance segmentation dataset
Preprocessing Applied:

Auto-orient: Automatically corrects image orientation
Rotation: Random rotation between -10° and +10° for data augmentation


Dataset Split: Train/Validation/Test split as shown in training results

Model Architecture

Framework: YOLOv11 (You Only Look Once version 11)
Task: Instance Segmentation
Input: Dental X-ray/clinical images
Output: Segmented dental structures with bounding boxes and masks

Key Features

State-of-the-art Performance: Leverages YOLOv11's improved architecture
Real-time Inference: Optimized for fast dental image analysis
Custom Training: Tailored specifically for dental imaging applications
Data Augmentation: Includes rotation and orientation correction

Requirements
See requirements.txt for a complete list of dependencies.
Key dependencies include:

ultralytics (YOLOv11)
torch
torchvision
opencv-python
numpy
matplotlib
Pillow
