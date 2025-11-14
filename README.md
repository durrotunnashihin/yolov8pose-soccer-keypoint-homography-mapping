# Evaluating YOLOv8-Pose Variants for Accurate Soccer Field Keypoint Detection and Homography Mapping
<img width="2078" height="1008" alt="Keypoint Detections-Page-1 (6)" src="https://github.com/user-attachments/assets/064aa621-87b0-466a-b2f1-fce84c00276e" />

## 📝 Overview
This repository provides the implementation, dataset, notebooks, and evaluation pipeline for the study “Evaluating YOLOv8-Pose Variants for Accurate Soccer Field Keypoint Detection and Homography Mapping.” 

The project investigates how different YOLOv8-Pose variants (Nano, Small, Medium, Large, X-Large) perform in detecting soccer field keypoints extracted from broadcast and scouting videos, and how well these predictions support homography estimation using DLT and RANSAC. 

The entire workflow is designed to be run inside Google Colab, and each notebook already includes an Install Libraries section **(no manual setup or pip install -r requirements.txt is required).**

## 🔍 Key Features
1. YOLOv8-Pose training & inference for soccer field keypoint detection
2. Evaluation of five YOLOv8-Pose variants: Nano, Small, Medium, Large, X-Large
3. Homography computation using Direct Linear Transform (DLT) and RANSAC
4. Notebook-based workflow with step-by-step execution
5. Benchmarking on:
  - Mean pixel error
  - Latency, FPS & model size
  - Homography reliability
  - Open dataset included for reproducibility (source: https://universe.roboflow.com/adzuki/soccer-field-localization)

## 🚀 How to Run (Google Collab)
1. Move all project files and folders into: **My Drive/Colab Notebooks/**
2. Make sure your structure looks like this:

   <img width="476" height="181" alt="image" src="https://github.com/user-attachments/assets/7f9ae358-8057-41ef-a39e-14bcaedf2fcd" />

4. Open the notebook (i.e., keypoint_detection_homography_mapping.ipynb) in Google Colab
5. Run the cells in order:
  - Install Libraries
  - Mount Google Drive
  - Load Dataset & Models
  - Run Keypoint Detection and Homography Mapping

Everything is preconfigured, **so no path editing is required.**

## 📜 Citation
If you use this repository, please cite:

xxx, x., & xxx, x. (2025). 
Evaluating YOLOv8-Pose Variants for Accurate Soccer Field Keypoint Detection and Homography Mapping.

## 🤝 Contributions
Contributions, pull requests, and discussions are welcome!
Feel free to open issues for bugs, suggestions, or improvements.

