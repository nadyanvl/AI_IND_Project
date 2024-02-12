# Coral Life Forms Detection for Analysis of Climate Change Impact on Coral Biodiversity

## Project Overview
This project focuses on utilizing the YOLO (You Only Look Once) real-time object detection system to detect coral life forms. The dataset comprises images of coral reefs obtained from a Remotely Operated Underwater Vehicle (ROV) survey, manually annotated for seven distinct coral forms. The primary aim is to analyze the impact of climate change on coral biodiversity in marine environments.

**Project Title:** Coral Life Forms Detection for Analysis of Climate Change Impact on Coral Biodiversity  

## Introduction
### Background
Coral reefs are vital ecosystems facing threats from climate change. NOAA predicts significant impacts, including sea level rise and altered ocean patterns, affecting coral biodiversity and ecosystem functions. Traditional coral assessment methods like Line Intercept Transect (LIT) have limitations, emphasizing the need for automated detection methods like YOLO.

### Objective & Scope
**Objective:** Develop deep learning models to identify and analyze seven coral life forms.  
**Scope:** Explore YOLO for coral life forms detection.

## Getting Started
### 1. Data Collection & Preparation
**Dataset:** [Coral Life Forms Detection](https://universe.roboflow.com/computer-vision-xiyu1/coral-life-forms-detection/dataset/3)

**Data Source:** ROV surveys in the North Bali Sea, manually annotated in Roboflow.

### 2. Model Development
**Model:** YOLO (You Only Look Once)  
**Architectural Variations:** YOLOv3u, YOLOv5s, and YOLOv8s  
**Hyperparameters:**
- Epoch: 100
- Batch_size: 16
- Img_size: 416
- Learning Rate (lr0): 0.01
- Final Learning Rate (lrf): 0.0001
- Momentum: 0.937
- Weight Decay: 0.0005
- Optimizer: AdamW

### 3. Training & Optimization
Training involves presenting the dataset to the YOLO architecture, optimizing for accuracy and efficiency. Evaluation metrics include Precision, Recall, mAP50, mAP(50-95), and inference time. 

**Validation Results:**

| Model   | Precision | Recall | mAP50 | mAP(50-95) | Inference time (ms) |
|---------|-----------|--------|-------|------------|---------------------|
| YOLOv3u | 0.816     | 0.778  | 0.810 | 0.644      | ±21                 |
| YOLOv5s | 0.755     | 0.510  | 0.562 | 0.310      | ±11                 |
| YOLOv8s | 0.859     | 0.779  | 0.829 | 0.637      | ±11                 |

## Conclusion
The project demonstrates the effectiveness of YOLO in coral life forms detection, with YOLOv8s showing the highest performance. Automated detection methods like YOLO offer efficient and scalable solutions for monitoring coral biodiversity, crucial for understanding and mitigating the impacts of climate change.
