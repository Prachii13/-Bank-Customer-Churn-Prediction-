# 🏦 Bank Customer Churn Prediction (KNN Classifier)

This project predicts whether a customer will leave the bank ("churn") using machine learning, specifically K-Nearest Neighbors (KNN).

## 📌 Dataset
- Source: Kaggle - Bank Customer Churn Prediction
- Features: Credit score, age, balance, product usage, etc.
- Target: `Attrition_Flag` — whether the customer left or stayed

## 🧠 Models Used
- K-Nearest Neighbors (KNN)
- Compared with Logistic Regression and Random Forest (for benchmarking)

## 🧪 Evaluation
- Confusion Matrix, Accuracy Score, Classification Report
- Feature Encoding + Normalization

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook churn_knn_classifier.ipynb
