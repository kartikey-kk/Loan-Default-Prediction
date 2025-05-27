# 💼 Loan Default Prediction with Random Forest

> 🎯 A complete pipeline for predicting loan defaults using a well-tuned Random Forest classifier — featuring data cleaning, feature engineering, hyperparameter optimization, evaluation metrics, and visualizations.

---

## 📂 Project Overview

This project demonstrates how to build an end-to-end ML pipeline for binary classification (loan default vs. no default) using the Random Forest algorithm. It includes:

- 💡 Data preprocessing & feature engineering
- 🧪 Stratified train-test splitting
- 🧰 Hyperparameter tuning using GridSearchCV
- 📊 Model performance evaluation
- 🔍 Feature importance visualization

---

## 📁 Dataset

| File                | Description                              |
|---------------------|------------------------------------------|
| `train_dataset.csv` | Training data with input features & labels |
| `test_file.csv`     | (Optional) New test data for prediction   |

---

## ⚙️ Features Used

- `Credit_History`
- `LoanAmountLog` (log-transformed)
- `TotalIncomeLog` (log-transformed)
- `Loan_Amount_Term`
- `Gender`, `Married`, `Education`, `Self_Employed`, `Property_Area`, `Dependents`

---

## 🔧 Workflow

```mermaid
flowchart TD
  A[Raw Data] --> B[Data Cleaning]
  B --> C[Feature Engineering]
  C --> D[Train-Test Split]
  D --> E[GridSearchCV Tuning]
  E --> F[Model Training]
  F --> G[Evaluation & Metrics]
  G --> H[Visualizations]
