# YOLO-project

##AI-Based Sperm Analysis for ICSI Selection
### Overview

This project presents an AI-based system for analyzing sperm cells to assist in selecting the best candidate for Intracytoplasmic Sperm Injection (ICSI).

### Project Description

The system uses computer vision and machine learning techniques to automatically analyze sperm samples. It performs multiple stages of processing to evaluate sperm quality and identify the most suitable sperm cell for fertilization.

The pipeline includes:

Detection of sperm cells in microscopy images/videos
Tracking individual sperm movement over time
Segmentation to isolate each sperm cell
Motion prediction to analyze movement behavior
Feature extraction (morphological and motility features)

These steps help in selecting the optimal sperm based on movement quality and physical characteristics.

### Objective

To improve the accuracy and efficiency of sperm selection in ICSI procedures by reducing manual effort and human error using AI.

### Project Structure
01_detection.ipynb
Detecting sperm cells in the input data
02_segmentation.ipynb
Segmenting individual cells
03_tracking_motion_prediction.ipynb
Tracking sperm and feature extraction, motion prediction, and final evaluation
### Technologies Used
Python
OpenCV
NumPy
Pandas
Scikit-learn
Deep Learning / Computer Vision techniques
### How to Run
Open the notebooks using Jupyter Notebook or Google Colab
Run each notebook in order
Ensure all required libraries are installed
### Results

The system successfully analyzes sperm characteristics and identifies high-quality candidates based on motility and morphology features.
