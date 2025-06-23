# COVID19-XRay-Classification
# 🦠 COVID-19 X-Ray Image Classification

This project classifies chest X-ray images into categories such as **COVID-19**, **Viral Pneumonia**, and **Normal** using deep learning and transfer learning techniques.

## 📌 Project Overview

- ✅ Built with TensorFlow/Keras
- ✅ Uses pre-trained models like Xception, VGG16, MobileNetV2, etc.
- ✅ Augments and processes image data for better performance
- ✅ Applies Transfer Learning for high accuracy in medical imaging

## 📂 Dataset

- Source: [Kaggle Dataset](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset)
- Structure:
  - `train/` — Labeled X-ray images
  - `test/` — Unlabeled images for evaluation

## 🧠 Model Architecture

- Utilizes pre-trained CNN models with custom top layers
- Input shape: `224x224x3`
- Output: Softmax over 3 classes
- Data augmentation: Rotation, zoom, shear, flip
- Trained with categorical crossentropy loss and Adam optimizer

## 📈 Results

> Accuracy: _To be filled after training_  
> Validation Accuracy: _To be filled_  
> Confusion Matrix & classification report included

## 🚀 How to Run

```bash
# Upload your kaggle.json and download dataset
# Run all cells in the notebook on Google Colab
