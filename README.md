# Smart Selfie – Face Detection & Recognition Project

## Overview
Smart Selfie is a computer vision project that uses OpenCV, dlib, and face_recognition to perform real-time face detection, smile recognition, and age prediction.  
The goal is to build a reliable pipeline that can capture live video, detect faces, preprocess images, and apply machine learning models for classification.

## Features
- Real-time webcam access with OpenCV  
- Face detection using OpenCV Haar Cascades and dlib  
- Image preprocessing (resizing, normalization, grayscale conversion)  
- Dataset handling with augmentation and splitting  
- Training-ready pipelines for smile detection and age prediction  

## Project Structure
Dlip_Vscode/
│── .gitignore
│── requirements.txt
│── README.md
│── src/
│ ├── main.py # Entry point for the project
│ ├── camera_test.py # Webcam testing script
│ └── preprocessing.py # (future) image preprocessing utilities
│── dlib_venv/ # Virtual environment (ignored in git)