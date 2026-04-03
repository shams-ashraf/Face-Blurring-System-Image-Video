# 🚀 Face Anonymization System (Image & Video)

## 🧠 Overview
This project implements a real-time face anonymization system for both images and live video streams.  
It combines deep learning-based face detection with multiple anonymization strategies and controlled intensity levels.

---

## ✨ Features
- 🔍 Face detection using a deep learning model (SSD - Caffe)
- 🎬 Real-time anonymization for webcam video
- 🖼️ Image-based anonymization
- 🎛️ Adjustable anonymization intensity levels
- ⚙️ Dynamic control of anonymization during video processing

---

## 🧪 Experimental Analysis
- Evaluated different blurring approaches across varying intensity levels  
- Compared face detection performance on original vs preprocessed images  
- Designed a blur intensity metric to quantify anonymization strength  
- Mapped anonymization outputs into discrete, controllable levels  

---

## 🧠 System Pipeline
1. Preprocess input images (denoising + contrast enhancement)
2. Detect faces using a deep learning model
3. Apply anonymization based on selected intensity level
4. Allow real-time adjustment during video processing

---

## 🛠 Technologies Used
- Python  
- OpenCV  
- NumPy  
- Deep Learning (SSD - Caffe Model)  

---

## ▶️ Usage
### Run Video Anonymization
```bash
python vedioDetection.py

Controls
G → Gaussian mode
M → Median mode
A → Average mode
+ / - → Increase / decrease intensity
ESC → Exit

## 📷 Demo

### 🖼️ Image-Based Anonymization
<img width="183" height="287" alt="image" src="https://github.com/user-attachments/assets/06e57637-2023-4da9-974e-80e20f40337a" />

---

### 🎬 Real-Time Video Anonymization
https://www.linkedin.com/posts/mariam-hassan-44b756261_computervision-imageprocessing-opencv-ugcPost-7411043915572879360-ez7L?utm_source=share&utm_medium=member_android&rcm=ACoAAEnTwDsBR6avacm33WuyPun6jfmJm_l3Qog
![Live Demo](images/demo.gif)
