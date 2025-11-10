# 🫀 Heart Disease Prediction with Deep Learning

## 📘 Overview

This project uses Deep Learning to predict the presence of heart disease based on patient health data.  
The model is built using **TensorFlow** and **Keras**, and trained to classify whether a patient has heart disease or not using various clinical features.

The goal is to demonstrate how a neural network can learn patterns from tabular health data and assist in early detection of heart disease.

---

## 🎯 Objectives

- Understand fundamentals of deep learning and neural networks.  
- Build a classification model using TensorFlow and Keras.  
- Train the model on clinical health data to predict heart disease.  
- Evaluate model performance using accuracy, confusion matrix, and classification report.  
- Handle class imbalance and optimize model learning.

---

## 🧩 Dataset

- **Dataset:** Heart Disease Prediction Dataset (Kaggle)  
- **Description:** Contains patient health records with features like age, sex, chest pain type, blood pressure, cholesterol, fasting blood sugar, and more.  
- **Target variable:** `output` → 1 (Heart Disease) / 0 (No Heart Disease)  
- **Split:** 80% for training, 20% for testing  

---

## ⚙️ Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  

---

## 🔍 Model Architecture

The neural network is a **Sequential model** composed of:

- **Dense Layer (128 neurons)** – Learns complex features using ReLU activation.  
- **Dropout Layer (0.3)** – Prevents overfitting.  
- **Dense Layer (64 neurons)** – Further feature extraction with ReLU activation.  
- **Dropout Layer (0.3)** – Additional regularization.  
- **Dense Output Layer (1 neuron)** – Sigmoid activation for binary classification.  

**Compiled with:** Adam optimizer and `binary_crossentropy` loss function.

---

## 🚀 Steps Performed

1. Loaded the dataset from Kaggle using `kagglehub`.  
2. Preprocessed the data: handled categorical variables, normalized features with `StandardScaler`.  
3. Split data into training and testing sets.  
4. Computed class weights to address imbalance.  
5. Built and compiled a neural network with Keras.  
6. Trained the model for 100 epochs with class weights applied.  
7. Evaluated model performance using accuracy, confusion matrix, and classification report.  
8. Plotted training vs validation accuracy and loss.  
9. Saved the trained model in Keras format (`.keras`).  

---

## 📊 Results

- **Training Accuracy:** 61.11%  
- **Test Accuracy:** 74.07%  
- **Confusion Matrix:** Shows model performance across both classes  
- **Classification Report:** Precision, Recall, and F1-score metrics for both classes  


---

## 💡 Insights

- Handling class imbalance significantly improves prediction for the minority class.  
- Feature scaling accelerates training and stabilizes the learning process.  
- Even a simple neural network with 2 hidden layers can achieve strong performance on tabular datasets.

---

## 🔗 Notebook Link
https://colab.research.google.com/drive/1SVme4X-pA_pMaQb5W77cpNMHOelNuSaC?usp=sharing
