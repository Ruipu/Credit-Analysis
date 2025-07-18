# 💳 Credit Card Approval Prediction

This project explores and models a credit card approval dataset using both **Exploratory Data Analysis (EDA)** and **Machine Learning** techniques.

## 📊 Project Overview

The main goal of this project is to analyze applicant features and predict whether a credit card application is approved (`1`) or rejected (`0`).

- Performed EDA to understand the data distribution, class imbalance, and feature relationships
- Built multiple classification models (Logistic Regression, Random Forest, SVM)
- Tuned hyperparameters using GridSearchCV
- Handled class imbalance using SMOTE
- Evaluated model performance using metrics such as accuracy, F1-score, confusion matrix, and ROC-AUC
- Visualized top feature importances from Random Forest
- Combined models using a soft voting classifier to boost performance

## 📁 Files

- `credit_eda.ipynb`: Exploratory Data Analysis (EDA) notebook
- `credit_modeling.ipynb`: Model building, evaluation, and improvement notebook

## 🔧 Tech Stack

- Python
- pandas, seaborn, matplotlib
- scikit-learn, imbalanced-learn
- Jupyter Notebook

## 📌 Key Results

- Best F1 Score from GridSearchCV: **0.836**
- ROC-AUC of best classifier: **0.95**
- Soft Voting Classifier Accuracy: **0.891**

## 🚀 Future Work

- Deploy model using Streamlit or Flask
- Add SHAP-based interpretability for feature impact
- Explore XGBoost and LightGBM classifiers

---

*Feel free to clone, fork, or star this repo if you find it useful!*
