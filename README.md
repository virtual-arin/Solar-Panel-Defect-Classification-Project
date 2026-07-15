# ☀️ Solar Panel Defect Detection System

## 🛡️ Business Domain
Renewable Energy

---

## 🤔 Problem Statement

Solar power plants contain thousands of solar panels spread across large areas. Over time, panels may develop defects such as **dust accumulation, bird droppings, electrical damage, physical damage, and snow coverage**, reducing their efficiency and power generation.

Manual inspection is time-consuming, expensive, and often inaccurate, especially for large-scale solar farms.

This project develops a **Deep Learning-based Solar Panel Defect Detection System** that automatically classifies solar panel images into different defect categories, enabling faster maintenance, minimizing energy loss, and improving the overall efficiency of solar power systems.

---

## 🎯 Project Objective

The objective of this project is to build a **multi-class image classification model** using **Convolutional Neural Networks (CNN)** and **Transfer Learning (EfficientNetB0)** to automatically identify different types of solar panel defects from images.

---

## 📈 Dataset Overview

- **Input:** RGB Images of Solar Panels
- **Image Size:** 224 × 224 pixels
- **Classes (6):**
  - Clean
  - Dusty
  - Bird Drop
  - Electrical Damage
  - Physical Damage
  - Snow Covered
- **Problem Type:** Multi-Class Image Classification
- **Algorithms:**
  - Convolutional Neural Network (CNN)
  - Transfer Learning (EfficientNetB0)

---

## 🛠️ Tech Stack

**Language**
- Python

**Libraries**
- NumPy
- Pandas
- Matplotlib
- TensorFlow
- Keras
- Pillow

**Deep Learning**
- Convolutional Neural Networks (CNN)
- EfficientNetB0 (Transfer Learning)

**Web Framework**
- Streamlit

**Development Environment**
- Jupyter Notebook

---

## 🔄 Project Workflow

1. Data Collection
2. Data Preprocessing
3. Image Augmentation
4. CNN Model Development
5. Transfer Learning using EfficientNetB0
6. Model Training
7. Model Evaluation
8. Model Saving
9. Streamlit Web Application Development

---

## 🚀 Streamlit Application

The application allows users to:

- Upload a solar panel image.
- Automatically detect the defect category.
- Display the prediction confidence.
- View the probability for each defect class.

### 💡 Supported Defect Classes

- ✅ Clean
- 🌫️ Dusty
- 🐦 Bird Drop
- ⚡ Electrical Damage
- 🔨 Physical Damage
- ❄️ Snow Covered

---

## 🔮 Future Improvements

- Real-time drone-based solar panel inspection
- Thermal image integration
- Defect localization using YOLO/Mask R-CNN
- Cloud deployment (AWS/Azure/GCP)
- REST API integration
- Mobile application for field engineers
- Predictive maintenance dashboard
