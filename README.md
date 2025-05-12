# Paddy Crop Leaf Disease Prediction using MobileNet

## 🔍 Project Overview

This project uses **MobileNet**, a lightweight and efficient deep learning architecture, to classify paddy crop leaves into various disease categories. The model helps farmers and agricultural experts identify diseases early and take preventive measures.

## 🧠 Model

I used the **MobileNet architecture**, pretrained on ImageNet, and fine-tuned it on a custom paddy crop disease dataset consisting of 10 categories (9 diseases + 1 healthy leaf).

## 📂 Dataset

- The dataset contains 10 folders, each representing a class:
  - Bacterial Leaf Blight
  - Bacterial Leaf Streak
  - Bacterial Panicle Leaf 
  - Brown Spot
  - Leaf Blast
  - Dead Heart
  - Downy Mildew
  - Hispa
  - Tungro
  - (add Normal Healthy Leaf)
- All images are resized to `224x224` for preprocessing.

## ✅ Achievements

- **Accuracy:** 96%
- **Model Size:** Lightweight and optimized for mobile/IoT devices
- **Platform:** Trained using TensorFlow/Keras

## 📊 Results

| Class                    | Precision | Recall | F1-Score |
|--------------------------|-----------|--------|----------|
| Bacterial Leaf Blight    | 0.91     | 0.85   | 0.88     |
| Bacterial Leaf Streak    | 0.97     | 0.95   | 0.96     |
| Bacterial Panicle Blight | 1.00     | 0.97   | 0.98     |
| Blast                    | 0.96     | 0.97   | 0.97     |
| Brown Spot               | 0.94     | 0.99   | 0.96     |
| Dead Heart               | 0.99     | 0.99   | 0.99     |
| Downy Mildew             | 0.88     | 0.98   | 0.93     |
| Hispa                    | 0.94     | 0.94   | 0.94     |
| Tungro                   | 0.94     | 0.97   | 0.95     |
| Normal                   | 0.99     | 0.93   | 0.96     |
