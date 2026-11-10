# YOLOv5 Based Real-Time Sign Language Gesture Recognition and Text Conversion System

This repository contains the dataset and code for the project "Sign Language to Text Converter using YOLOv5".

The aim of this project is to help bridge communication gaps by detecting sign language gestures in real-time and converting them into readable text.

## 📂 Contents

1.`YOLOV5.v1\yolov5pytorch.zip`: Pre-trained YOLOv5 model and related files.

2.`yolov5.ipynb`: Google Colab notebook to train, test, and run inference on images.

3.`Liveweb Cam`: Jupyter Notebook for real-time detection using a live webcam.

4.`YOLO-V5 (dataset)`: Dataset of sign language gesture images.

## 🗂️ Dataset

The `YOLO-V5 (dataset)` folder contains the collected sign language gesture images used for this project.


## 🏗️ System Architecture

<img width="2800" height="1660" alt="architecture" src="https://github.com/user-attachments/assets/7f7bdf46-586a-4abd-8aaa-efca0cee47b5" />


## ⚙️ Project Overview
The model is trained to recognize specific sign language gestures.Once detected, the recognized gesture is converted into text for easier understanding and communication.Built and tested using Google Colab.

The output can be viewed in two ways:
- Image input (Google Colab): Upload an image and view the detected gesture as text.
- Real-time (Jupyter Notebook): Use a live webcam for continuous detection.

## ✅ Setup
1. Clone this repository.
2. Extract the ZIP file containing the YOLOv5 model.

Option 1: Image Input (Google Colab)
1. Open `yolov5.ipynb` in Google Colab.
2. Run the cells in order and upload a test image.

Option 2: Real-Time Detection (Jupyter Notebook)
1. Install the dependencies
2. Open `Liveweb Cam` in Jupyter Notebook.
3. Make sure a webcam is connected, then run the cells.
4. Press `q` to close the webcam window.

## 🚀 Technologies

-Python

-Open Cv

-Roboflow

-YOLOv5

-PyTorch

-Jupyter Notebook

-Google Colab
