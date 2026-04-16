# Human-Activity-Recognition-using-Quantized-CNN
This project focuses on recognizing human activities such as walking, sitting, standing, and lying using sensor data from smartphones. Machine learning algorithms are applied to preprocess the data, extract meaningful features, and classify with high accuracy. The model is trained and evaluated on a labeled dataset to ensure reliable performance.

## 📌 Overview
This project implements a real-time Human Activity Recognition (HAR) system using deep learning and computer vision techniques. The system detects and classifies human activities from live video input using a Convolutional Neural Network (CNN) optimized with quantization for efficient deployment on edge devices like Raspberry Pi.

---

## 🎯 Objectives
- Develop a real-time activity recognition system
- Classify human activities using CNN
- Apply preprocessing techniques for improved performance
- Optimize the model using quantization (INT8)
- Deploy the model on Raspberry Pi for edge computing
- Achieve low latency and efficient inference

---

## 🚀 Features
- Real-time activity detection using live video
- CNN-based deep learning model
- Model quantization for faster inference
- Edge deployment on Raspberry Pi
- Prediction smoothing for stable outputs
- Lightweight and efficient system

---

## 🧠 Technologies Used
- Python
- OpenCV
- NumPy
- TensorFlow
- ONNX
- OpenCV DNN Module
- Raspberry Pi
- Picamera2

---

## 🏗️ System Architecture
The system follows this pipeline:

1. Video Capture using Raspberry Pi Camera  
2. Frame Preprocessing (Resizing + Normalization)  
3. CNN Model Inference  
4. Prediction Smoothing  
5. Output Display with Activity Label  

---

## 📂 Dataset
- Contains **15 activity classes** such as:
  - Sitting
  - Running
  - Eating
  - Texting
  - Dancing
  - Drinking
  - Calling
  - Cycling

- Images vary in:
  - Lighting conditions
  - Backgrounds
  - Camera angles  

---

## ⚙️ Preprocessing
- Image resizing to **128 × 128**
- Pixel normalization (0–1)
- Label encoding
- Data augmentation (rotation, flipping, brightness)

---

## 🧠 Model Details
- Model: Convolutional Neural Network (CNN)
- Activation: ReLU
- Optimizer: Adam
- Loss Function: Categorical Crossentropy
- Output: Softmax classification

---

## ⚡ Quantization
- Converted model from **FP32 → INT8**
- Benefits:
  - Reduced model size (~75%)
  - Faster inference
  - Lower memory usage
  - Suitable for Raspberry Pi

---

## 📊 Performance
- High training and validation accuracy
- Confusion matrix used for evaluation
- ROC and Precision-Recall analysis performed
- Real-time performance achieved with low latency

---

## 🔄 System Pipeline
