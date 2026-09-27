# 📌 Project Overview

Customer churn prediction is a binary classification problem where the goal is to identify customers who are likely to leave a service.

In this project, multiple machine learning algorithms were trained and compared:

- Logistic Regression
- Random Forest
- XGBoost
- Support Vector Classifier (SVC)

Different preprocessing strategies were used depending on the model:

- One-hot encoding for categorical features
- Feature scaling for models sensitive to feature magnitude
- Encoded features for tree-based models

---

## 🎯 Objective

The main objectives of this project are:

- Predict customer churn
- Compare different classification algorithms
- Analyze model generalization
- Identify and reduce overfitting
- Handle categorical features correctly
- Evaluate performance using more than just accuracy
- Analyze the effect of class imbalance on model predictions

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Train-Test Split
     ↓
Categorical Feature Encoding
     ↓
Feature Scaling
     ↓
Model Training
     ↓
Model Evaluation
     ↓
Overfitting Analysis
     ↓
Model Tuning
