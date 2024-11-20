# Face and Object Detection

This project demonstrates a variety of computer vision techniques for face and object detection. The implementation leverages popular algorithms like Haar Cascades and HOG (Histogram of Oriented Gradients) for detecting faces, eyes, and other objects in images.

## Table of Contents
- [Project Overview](#project-overview)
- [Files Included](#files-included)
- [Requirements](#requirements)
- [Usage](#usage)
- [License](#license)

## Project Overview

This project aims to provide a simple implementation of face and object detection using classical computer vision techniques such as:
- Haar Cascade Classifiers
- HOG (Histogram of Oriented Gradients) with Support Vector Machine (SVM)
- Object tracking techniques

It includes several Python scripts and Jupyter notebooks that demonstrate these techniques on sample images and videos.

## Files Included

- `Detecting_and_cartooning_an_image.ipynb`: A Jupyter notebook for detecting faces and applying cartoon filters to images.
- `HOG_SVM.ipynb`: A Jupyter notebook demonstrating object detection using HOG features with SVM for classification.
- `Haar-eye-detection.py`: Python script for detecting eyes in images using Haar Cascade classifiers.
- `Haar-face-detection.py`: Python script for detecting faces using Haar Cascade classifiers.
- `ball_detection.py`: Script for detecting and tracking a ball in a video.
- `ball_detection_and_tracking.py`: Script to detect and track the movement of a ball using object detection and tracking techniques.
- `read_display_save.py`: Python script for reading an image, displaying it, and saving the result after processing.
- `git.code-workspace`: Visual Studio Code workspace configuration.

## Requirements

To run the scripts in this project, you'll need the following Python libraries:

- `opencv-python`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `imutils`

You can install the required dependencies using `pip`:

```bash
pip install opencv-python numpy matplotlib scikit-learn imutils
