# AI-Medical-Image-Analysis
AI-powered system for detecting pneumonia from chest X-ray images using deep learning (MobileNetV2).

# 🩺 AI-Powered Medical Image Analysis System

## 📌 Project Overview
This project is an AI-based system designed to analyze medical images (Chest X-rays) and detect Pneumonia using Deep Learning.

The model uses **Transfer Learning with MobileNetV2**, a lightweight and efficient convolutional neural network, to classify images into two categories:
- NORMAL
- PNEUMONIA

This project simulates a real-world healthcare application where AI assists doctors in faster and more accurate diagnosis.

---

## 🎯 Objectives
- Automate disease detection using AI
- Assist healthcare professionals in diagnosis
- Reduce human error in medical image analysis
- Build a real-world, industry-level AI project

---

## 🧠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

## 🏗️ Project Architecture

Medical Image → Preprocessing → Feature Extraction (CNN) → Model Prediction → Output

---

## 📊 Dataset

This project uses the **Chest X-ray Pneumonia Dataset**.

Download from:
https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

### 📁 Dataset Structure
AI-Medical-Image-Analysis/
│
├── src/
│ ├── preprocess.py
│ ├── model.py
│ ├── train.py
│ ├── predict.py
│
├── images/ # Screenshots (graphs, outputs)
├── models/ # Saved model
│
├── main.py
├── requirements.txt
├── README.md
├── .gitignore


---

## ⚙️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/AI-Medical-Image-Analysis.git
cd AI-Medical-Image-Analysis

pip install -r requirements.txt

Author
Ishwari Belhekar
