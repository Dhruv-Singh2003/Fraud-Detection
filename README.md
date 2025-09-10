# 💳 Fraud Detection using Machine Learning

## 📌 Project Overview

This project aims to detect fraudulent transactions using supervised machine learning techniques. With the rise of digital transactions, financial fraud has become increasingly common, making it critical to develop systems that can automatically detect and prevent fraud in real time.

We use a well-known anonymized dataset from Kaggle, which contains European cardholders’ transactions over two days in September 2013. 

---


## 🧠 Machine Learning Models Used

- Logistic Regression

---

## 🔧 Project Steps

1. **Data Loading & Exploration**
2. **Data Preprocessing**
   - Feature scaling using `StandardScaler`
   - Handling imbalanced classes
3. **Train-Test Split**
4. **Model Training**
5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

---

## 📈 Evaluation Metrics

Since the dataset is highly imbalanced, accuracy alone is not reliable. Instead, we focus on:

- **Precision**: How many predicted frauds are actually fraud.
- **Recall**: How many actual frauds are correctly identified.
- **F1 Score**: Harmonic mean of precision and recall.
- **ROC-AUC**: Measures classifier’s ability to distinguish between classes.

---


pip install -r requirements.txt
jupyter notebook
