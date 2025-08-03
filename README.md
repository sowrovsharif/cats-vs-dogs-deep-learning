# 🐶🐱 Cats vs Dogs Image Classifier

A deep learning-powered image classifier that distinguishes between cat and dog images using a Convolutional Neural Network (CNN) with transfer learning. Deployed as a Flask-based web app and hosted on **Heroku**.

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/Python-3.10-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.0+-orange)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

---

## 📌 Project Overview

This project uses **Google's MobileNetV2** as the base for transfer learning to classify images of cats and dogs. It’s optimized for performance and designed for easy web deployment with Flask.

- **Accuracy**: ~92%  
- **Loss**: ~19%  
- **Training Time**: ~30 mins/epoch (GPU)  
- **Deployment**: Flask + Heroku  
- **Dataset**: [Kaggle Cats vs Dogs Dataset](https://www.kaggle.com/datasets)

---

## 🧠 Model Architecture

- **Input Shape**: `(128, 128, 3)` RGB  
- **Base Model**: `MobileNetV2 (imagenet weights)`  
- **Head**: Custom fully connected layers  
- **Activation**: ReLU  
- **Optimizer**: RMSprop  
- **Loss**: Binary Crossentropy  
- **Metric**: Accuracy  

> Model trained using TensorFlow 2.0 (GPU)  
> Stored as: `catsVSdogs.h5`

---

## 🧰 Tech Stack

### 🔬 Deep Learning
- TensorFlow 2.0+
- Keras
- scikit-image
- NumPy
- Pandas
- h5py

### 🌐 Web Development
- Flask
- HTML5, CSS3
- Bootstrap & Materialize CSS

### ⚙️ DevOps
- Travis CI
- Heroku (deployment)

---


