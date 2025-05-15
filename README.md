# 🤖 Twitter Bot Detection using Machine Learning & Deep Learning
Comparitive study on bot detection on twitter/X using Traditional, Ensemble and Deep Learning Models


This project focuses on detecting bot accounts on Twitter using a balanced dataset and multiple classification models. It combines both traditional **machine learning algorithms** (Random Forest, XGBoost, Logistic Regression, K-Nearest Neighbors) and **deep learning models** (CNN, LSTM) to achieve high accuracy and reliable classification.

---

## 📌 Project Overview

Social media platforms are increasingly affected by bots that automate interactions, spread misinformation, or skew conversations. Detecting such bot accounts is crucial for maintaining trust and integrity on platforms like Twitter.

This project builds and compares several models to classify accounts as either **bots** or **humans** using account metadata.

## 📊 Dataset

- **File:** `twitter_human_bots_dataset(2).csv`
- **Target column:** `account_type` (`bot` or `human`)
- **Feature types:**
  - Account statistics (followers, tweets, retweets, etc.)
  - Profile metadata

---

## 🧠 Models Implemented

### 🔹 Ensemble Machine Learning
1. **Random Forest Classifier**
2. **XGBoost Classifier**

### 🔹 Traditional Machine Learning
3. **K-Nearest Neighbors (KNN)**
4. **Logistic Regression**

### 🔹 Deep Learning
5. **Convolutional Neural Network (CNN)**
6. **Long Short-Term Memory (LSTM)**


---

## 📈 Evaluation Metrics

Each model is evaluated on:

- Training Accuracy
- Validation Accuracy
- Test Accuracy
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix

