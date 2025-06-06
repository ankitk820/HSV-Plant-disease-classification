# 🌿 Plant Leaf Disease Classification using ML & DL Approaches
This repository presents a hybrid framework for identifying plant leaf diseases using classical **Machine Learning** (ML) algorithms and compares their performance with **Deep Learning** (DL) architectures. The goal is to provide an efficient, accurate, and accessible solution for disease diagnosis in plants, particularly grape leaves, supporting timely agricultural decision-making.
## 📋 Project Description
Various plant leaves are used in daily life for cooking, medicine, and agriculture. However, plant diseases have a significant impact on crop yield and quality. Accurate and timely diagnosis of these diseases is crucial for effective management.
This project proposes a framework that:
- Extracts image features using **segmented HSV histogram analysis**.
- Classifies the leaves using traditional ML models:
  - **Support Vector Machine (SVM)**
  - **Logistic Regression**
  - **Random Forest**
- Compares the results with three deep learning CNN models:
  - **ResNet50**
  - **EfficientNetB0**
  - **InceptionV3**
## 🧪 Dataset
The experiments are performed on the **PlantVillage Grape Leaf Dataset**, which includes three common grape leaf diseases:
1. 🍇 **Black Rot**
2. 🍇 **Black Measles**
3. 🍇 **Leaf Blight**
## 🧠 Models and Accuracy
| Model              | Accuracy (%) |
|-------------------|--------------|
| Logistic Regression | 96.11%       |
| SVM                | 95.41%       |
| Random Forest      | 94.17%       |
| ResNet50 (DL)      | Lower (no fine-tuning) |
| EfficientNetB0 (DL)| Lower (no fine-tuning) |
| InceptionV3 (DL)   | Lower (no fine-tuning) |
> ML models outperformed unoptimized DL models and offer fast, lightweight performance, making them ideal for **low-resource platforms** such as mobile and edge AI devices.
## 🧰 Features

- Feature extraction using **HSV color histograms** on segmented leaf regions.
- Multi-model evaluation and benchmarking.
- ML classifiers with high accuracy and low computational cost.
- Comparative study with CNN-based deep learning models.
## 📈 Future Work
- Fine-tuning and training of deep learning models for improved accuracy.
- Integration with **Explainable AI (XAI)** techniques like Grad-CAM.
- Deployment on mobile or IoT edge devices for real-time diagnosis.
## 🗃️ Folder Structure (Recommended)
```bash
📂 plant-disease-classification/
├── 📁 data/              # Dataset or links to Kaggle
├── 📁 models/            # Saved ML models (optional)
├── 📁 notebooks/         # Jupyter notebooks (Kaggle/Colab)
├── 📁 results/           # Plots, confusion matrix, accuracy graphs
├── 📄 README.md          # Project overview
├── 📄 requirements.txt   # Dependencies (optional)
