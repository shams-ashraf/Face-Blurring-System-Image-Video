# 🚀 Face Blurring System (Image & Video)

## 🧠 Overview
This project implements a face blurring system that detects faces and applies different blurring techniques to protect privacy.

The system works on:
- 🖼️ Images   
- 📷 Live webcam  

It uses a deep learning model for face detection and OpenCV for image processing.

---

## ✨ Features
- 🔍 Face detection using a pre-trained model  
- 🎬 Real-time face blurring in video  
- 🖼️ Image-based face blurring  
- 🎛️ Multiple blur types:
  - Gaussian Blur  
  - Median Blur  
  - Average Blur  
- ⚙️ Adjustable blur strength (kernel size)  
- ⌨️ Keyboard controls during video:
  - G → Gaussian  
  - M → Median  
  - A → Average  
  - + / - → Increase or decrease blur  

---

## 🧠 How It Works
1. Detect faces using a deep learning model  
2. Extract face regions  
3. Apply selected blur technique  
4. Display the processed image/video  

---

## 🛠 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Deep Learning (SSD - Caffe Model)  

---
