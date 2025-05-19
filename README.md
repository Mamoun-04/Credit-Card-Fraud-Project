# 🧠 Credit Card Fraud Detection System

This project is a machine learning pipeline designed to detect fraudulent credit card transactions with exceptionally high precision on highly imbalanced datasets.

## 🚀 Project Summary

Built using Python, Scikit-learn, and TensorFlow, this model achieved an **F1-score of 0.9998**, misclassifying only **1 transaction out of 50,000**.

Fraudulent transactions are rare, and detecting them accurately without overfitting is a major challenge. This project addresses that by using advanced resampling techniques and a carefully engineered pipeline.

---

## 📊 Techniques Used

- **SMOTE + Tomek Links** for handling severe class imbalance  
- **Scikit-learn Pipelines** for reproducible preprocessing and model tuning  
- **TensorFlow** for scalable real-time inference  
- **GridSearchCV** for hyperparameter optimization  
- **Confusion Matrix & ROC-AUC** for performance evaluation

---

## 🧪 Dataset

The dataset was sourced from the [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud), containing anonymized transaction data for European cardholders.

- **Total transactions**: 284,807  
- **Fraudulent**: 492  
- **Normal**: 284,315  
- **Imbalance ratio**: ~1 in 580

---

## 📈 Results

- **F1-Score**: 0.9998  
- **Precision**: 0.9999  
- **Recall**: 0.9997  
- **Only 1 misclassified transaction out of 50,000**

---

## 🛠 Tech Stack

- Python  
- Scikit-learn  
- TensorFlow  
- Pandas / NumPy  
- Matplotlib / Seaborn  

---

## 📂 Project Structure

