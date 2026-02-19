# Credit Card Fraud Detection

A machine learning project to detect fraudulent credit card transactions using logistic regression and random forest classifiers, with interpretable feature analysis using SHAP.

---

## Project Overview

This project predicts credit card fraud from transaction data. It includes data preprocessing, model training, evaluation, and feature interpretation using SHAP. The dataset (`creditcard.csv`) should be placed in the project folder.

---

## Technologies & Tools

- Python  
- pandas, numpy, scikit-learn, matplotlib, seaborn, shap

---

## Features

- Data preprocessing: handling imbalanced data, feature scaling  
- Model training: Logistic Regression and Random Forest  
- Model evaluation: accuracy, feature importance plots  
- Model interpretation with SHAP

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/89Jaiveer/credit_card_fraud_detection.git
cd credit_card_fraud_detection
```
2. Install dependencies
```bash
pip install -r requirements.txt
```
3. Dataset
   Place creditcard.csv in the project folder before running the notebook

How to Run
Open interpretation.ipynb in Jupyter Notebook
Execute the following steps:
* Load and explore the dataset
* Split and scale features
* Train Logistic Regression and Random Forest models
* Visualize top features
* Apply SHAP for model interpretability

Created by Jaiveer Singh Khanuja
