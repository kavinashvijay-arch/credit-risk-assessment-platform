# 💳 Credit Risk Assessment & Loan Decision System

![Python](https://img.shields.io/badge/Python-3.11-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-red)
![SHAP](https://img.shields.io/badge/Explainable-AI-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 🚀 Run the Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1yJm7uQgCXOa-OPGWkbEP0gbB5uyRNxtn?usp=drive_link)

---

# 📌 Project Overview

Banks and financial institutions must accurately assess borrower risk before approving loans. Poor lending decisions increase default rates and financial losses. This project develops an end-to-end credit risk assessment system that predicts borrower default probability using machine learning and supports lending decisions through Expected Loss modelling, stress testing, and risk-based pricing.

---

# 🎯 Business Problem

Traditional credit assessment often relies on fixed scoring rules that may not fully capture borrower risk. This project demonstrates how machine learning can improve credit risk assessment by:

- Predicting Probability of Default (PD)
- Quantifying portfolio losses
- Supporting loan approval decisions
- Recommending risk-based interest rates
- Explaining predictions using Explainable AI

---

# 📂 Dataset

- 1,000 loan applications
- 48 borrower features
- Binary classification
- Target Variable:
  - 0 = Non-default
  - 1 = Default

---

# ⚙ Project Workflow

```
Loan Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Train/Test Split
      │
      ▼
Model Training
      │
      ▼
Model Evaluation
      │
      ▼
Expected Loss Modelling
      │
      ▼
Stress Testing
      │
      ▼
Loan Decision Engine
      │
      ▼
SHAP Explainability
```

---

# 🤖 Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

# 💰 Financial Risk Analytics

The project calculates:

- Probability of Default (PD)
- Loss Given Default (LGD)
- Exposure at Default (EAD)
- Expected Loss (PD × LGD × EAD)
- Portfolio Expected Loss
- Risk Adjusted Profit

---

# 📈 Stress Testing

The portfolio is evaluated under stressed economic conditions by increasing default probabilities, allowing expected losses to be compared between normal and adverse scenarios.

---

# 🔍 Explainable AI

SHAP was integrated to provide transparent explanations for each prediction.

The model explains:

- Why a borrower was classified as high risk
- Most influential borrower characteristics
- Overall feature importance

---

# 📊 Key Features

✔ Probability of Default Prediction

✔ Loan Approval Recommendation

✔ Interest Rate Recommendation

✔ Portfolio Risk Analysis

✔ Expected Loss Modelling

✔ Stress Testing

✔ SHAP Explainability

---

# 📁 Repository Structure

```
Credit-Risk-System/
│
├── notebook.ipynb
├── README.md
├── dataset.csv
├── images/
└── requirements.txt
```

---

# 🛠 Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib

---

# 🚀 Future Improvements

- Probability Calibration
- Hyperparameter Optimisation
- Streamlit Dashboard
- Real-Time Loan Approval API
- Basel III Capital Calculation

---

# 👨‍💻 Author

**Kavinash Vijay**
