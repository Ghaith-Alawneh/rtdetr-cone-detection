# 🏎️ RT-DETR Cone Detection for Formula Student

Real-time blue and yellow cone detection for Formula Student-style tracks using a fine-tuned RT-DETR (Real-Time DEtection TRansformer).

This project implements an object detection pipeline specifically designed for perception tasks in autonomous racing environments using a monocular camera setup.

## 📊 Project Overview
* **Model:** RT-DETR (via Ultralytics)
* **Task:** Object Detection (Blue & Yellow Track Cones)
* **Framework:** PyTorch / Python

## 📂 Dataset
The model was trained on a custom dataset of traffic cone images representative of track boundaries. 
* **Split:** 80% Training (5,246 images) / 20% Validation (1,357 images). 
* **Format:** Standard YOLO/Ultralytics format (images and corresponding label text files).

## 📈 Training Results
The model was fine-tuned for 10 epochs and achieved excellent initial metrics, showing strong learning without overfitting. 

**Key Metrics (Epoch 10):**
* **mAP50:** 86.5%
* **Precision:** 91.9%
* **Recall:** 81.2%

