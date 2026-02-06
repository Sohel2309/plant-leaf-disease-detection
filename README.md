# plant-leaf-disease-detection
CNN-based image classification model for detecting potato leaf diseases (Healthy, Early Blight, Late Blight) using TensorFlow and Keras, with data augmentation and performance visualization.

# Potato Disease Classification using CNN

## 📌 Overview
This project uses a Convolutional Neural Network (CNN) to classify potato leaf images into
three categories: Healthy, Early Blight, and Late Blight.

## 🧠 Model
- Custom CNN built using TensorFlow/Keras
- Data augmentation applied to improve generalization
- Softmax classifier for multi-class prediction

 ## 📦 Trained Model

The trained model is saved in the `models/` directory in native Keras format (`.keras`) and can be loaded using:

import tensorflow as tf
model = tf.keras.models.load_model("models/1.keras")



## 📊 Dataset
- Source: PlantVillage (Kaggle)
- Classes: Healthy, Early Blight, Late Blight
- Images resized to 256×256

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

## 📈 Results
- Training & Validation Accuracy: <img width="882" height="434" alt="image" src="https://github.com/user-attachments/assets/44f99b9c-550a-44e7-bfd0-4398e8d23f68" />
- Training & Validation LOSS : <img width="371" height="536" alt="image" src="https://github.com/user-attachments/assets/d93c6e6b-a3b1-4102-9441-f2215fdc394f" />


## 🔍 Sample Predictions
<img width="1349" height="473" alt="image" src="https://github.com/user-attachments/assets/f35bf963-bb13-4194-847c-587a0162d598" />


## 📓 Notebook

The complete training and evaluation process is available in:
-- [potato/training.ipynb](potato/training.ipynb)


This notebook includes data loading, preprocessing, model training, evaluation, and visualization.

