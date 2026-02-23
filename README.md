# LANDSLIDE-DETECTION
Deep learning and geospatial analytics project using U-Net segmentation on multispectral satellite imagery to detect landslide-prone regions.

# Landslide Detection using Deep Learning 🌍

## 📌 Project Overview
This project detects landslide-prone areas using multispectral satellite imagery and a U-Net deep learning segmentation model.

## 🎯 Objective
To develop an automated system for landslide detection and spatial risk mapping to support disaster management.

## 📂 Dataset
Landslide4Sense dataset containing:
- Sentinel satellite imagery
- NDVI, slope, elevation features
- Ground truth segmentation masks

## Approach
1. Data preprocessing and tiling
2. U-Net model training
3. Loss function: BCE + Dice
4. Evaluation using Dice coefficient, precision, recall
5. GIS validation using ArcGIS

##  Results
Achieved high segmentation accuracy with strong overlap between predicted and ground truth masks.

##  Key Insights
- Terrain slope and vegetation patterns are strong predictors
- Model effectively identifies large landslide regions

##  Tech Stack
Python, TensorFlow, Keras, OpenCV, ArcGIS

##  How to Run
1. Install dependencies
2. Run training notebook
3. Load trained model for prediction

##  Impact
Provides a scalable AI-driven approach for environmental hazard monitoring.
