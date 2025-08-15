# Explainable-Machine-Learning-for-Breast-Cancer-Metastasis-Prediction

📌 Overview

This project implements an explainable machine learning pipeline to predict whether a breast cancer sample is Primary or Metastatic using clinical and genomic features. The dataset used is the MSK-IMPACT Breast Cancer (2025) dataset from cBioPortal. The goal is to improve early detection, enable risk stratification, and support personalised treatment decisions.

We evaluate multiple ML and DL models, apply SHAP for interpretability, and present insights on key predictors influencing metastasis.

🎯 Objectives

Build and evaluate models including Logistic Regression, Random Forest, XGBoost, CatBoost, and Multi-Layer Perceptron (MLP).

Explain predictions using SHAP values to highlight influential clinical/genomic factors.

Compare classical vs deep learning approaches for metastasis prediction.

Translate predictions into risk categories for clinical decision support.

📂 Dataset

Source: cBioPortal - MSK-IMPACT Breast Cancer (2025)
Features include:

Clinical: Sex, Ethnicity, Race, Primary Tumor Site, Overall Survival (Months), Overall Survival Status

Genomic: Mutation Count, MSI Score, Fraction Genome Altered, Tumor Purity, Gene Panel

Target: Sample Type (Primary or Metastasis)

🛠 Tech Stack

Language: Python 3.x

Libraries:

Data Handling: pandas, numpy

ML/DL Models: scikit-learn, xgboost, catboost, tensorflow.keras

Imbalanced Data: imblearn

Interpretability: shap

Visualization: matplotlib, seaborn

📑 Methodology

Data Preprocessing

Cleaning missing values

Encoding categorical variables

Feature scaling

Handling class imbalance with SMOTE

Model Development

Logistic Regression

Random Forest

XGBoost

CatBoost

Multi-Layer Perceptron (Keras)

Evaluation

Confusion Matrix

Classification Report (Precision, Recall, F1-score)

ROC-AUC curves

Model Interpretability

Global SHAP summary plots

Feature importance rankings

Individual patient prediction explanations

Risk Categorization

Probability-based classification into Low, Medium, High risk

📌 How to Run
# Clone the repository
https://github.com/bhuvaneshpamidakula164-stack/Explainable-Machine-Learning-for-Breast-Cancer-Metastasis-Prediction.git
# Open Jupyter Notebook
jupyter notebook


Open Breast Cancer.ipynb and run all cells.

👩‍⚕️ Author

Bhuvanesh Pamidakula
MSc Data Science
