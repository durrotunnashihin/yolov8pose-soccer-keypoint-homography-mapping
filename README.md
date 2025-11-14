# Evaluating YOLOv8-Pose Variants for Accurate Soccer Field Keypoint Detection and Homography Mapping
<img width="1039" height="504" alt="Keypoint Detections-Page-1 (7)" src="https://github.com/user-attachments/assets/32fbb063-5490-4bcd-9067-01ebbde1a2e9" />

## Overview
This repository provides the implementation, dataset, notebooks, and evaluation pipeline for the study “Evaluating YOLOv8-Pose Variants for Accurate Soccer Field Keypoint Detection and Homography Mapping.” 

The project investigates how different YOLOv8-Pose variants (Nano, Small, Medium, Large, X-Large) perform in detecting soccer field keypoints extracted from broadcast and scouting videos, and how well these predictions support homography estimation using DLT and RANSAC. 

The entire workflow is designed to be run inside Google Colab, and each notebook already includes an Install Libraries section — no manual setup or pip install -r requirements.txt is required.

## Key Features
1. YOLOv8-Pose training & inference for soccer field keypoint detection
2. Evaluation of five YOLOv8-Pose variants: Nano, Small, Medium, Large, X-Large
3. Homography computation using Direct Linear Transform (DLT) and RANSAC
4. Notebook-based workflow with step-by-step execution
5. Benchmarking on:
- Mean pixel error
- Latency, FPS & model size
- Homography reliability
- Open dataset included for reproducibility (source: )

