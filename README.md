# Real-Time Stress Detection System using Image Processing and Deep Learning

## Overview

The Real-Time Stress Detection System is a computer vision and deep learning–based application designed to detect stress levels from facial images in real time. The system uses image processing techniques to extract facial features and a deep learning model to classify stress levels automatically.

This project demonstrates the integration of image processing, deep learning, and real-time video capture for intelligent stress detection.

---

## Features

- Real-time face detection using webcam
- Facial feature extraction using image processing
- Stress level classification using deep learning model
- Fast and accurate predictions
- Scalable and modular architecture
- Easy integration with other monitoring systems

---

## Technologies Used

### Programming Language
- Python

### Libraries and Frameworks
- OpenCV – for image processing and face detection
- PyTorch – for deep learning model
- NumPy – for numerical operations
- Torchvision – for pretrained models and transformations

### Tools
- Webcam for real-time input
- VS Code / Python IDE

---

## How It Works

1. The webcam captures real-time video.
2. OpenCV detects faces from each frame.
3. The detected face is preprocessed (resized, normalized).
4. The deep learning model analyzes the image.
5. The system predicts stress level (e.g., Stressed / Not Stressed).
6. The result is displayed in real time.

---

## Model Used

This project uses a Convolutional Neural Network (CNN) built using PyTorch.

### Why CNN was used:
- CNNs are highly effective for image classification tasks
- Automatically extracts important facial features
- Provides high accuracy in emotion and stress detection
- Efficient for real-time applications

---

## Project Structure
