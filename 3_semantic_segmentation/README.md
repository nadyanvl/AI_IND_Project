# Semantic Segmentation of Urban Scene Using U-Net Architecture on Cityscapes Dataset

## Project Overview
This project explores semantic segmentation using the U-Net algorithm with the Cityscapes dataset. The goal is to develop a model for self-driving cars.

**Project Title:** Semantic Segmentation of Urban Scene Using U-Net Architecture on Cityscapes Dataset  

## Introduction
### Background
In Autonomous Driving Vehicles, accurate understanding of the surroundings is crucial. Semantic segmentation assigns class labels (e.g., Car, Road, Pedestrian) to each pixel in an image, aiding in decision-making.

### Objective & Scope
**Objective:** Develop a segmentation model (U-Net) on the CityScapes dataset.  
**Scope:** Complete the Deep Learning Development Cycle and create a model that contributes to autonomous driving technology.

## Getting Started
### 1. Data Collection & Preparation
**Dataset:** [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
The dataset provides high-resolution images and pixel-level annotations for semantic segmentation, vital for training models in autonomous driving.

### 2. Model Development
**Model:** U-Net  
U-Net's U-shaped architecture is well-suited for semantic segmentation tasks due to its ability to capture context and localize details effectively.

**Hyperparameters:**
- img_size: 416
- batch_size: 8
- epochs: 50
- num_classes: 12
- optimizer: Adam
- learning_rate: 0.0001
- loss: Categorical Crossentropy
- metrics: Accuracy

### 3. Training & Optimization
Training involves presenting the dataset to the U-Net architecture, optimizing for accuracy and efficiency.

**Evaluation Metrics:** Accuracy and Mean IOU  
Training and validation results are summarized in the table below:

| train_loss | train_accuracy  | val_loss | val_accuracy |
|------------|----------------|----------|--------------|
| 0.3588     |  0.8893        | 0.5523   | 0.8536       |

## Conclusion
The U-Net model demonstrates strong performance in semantic segmentation tasks on the Cityscapes dataset. This project contributes to the advancement of autonomous driving technology.
