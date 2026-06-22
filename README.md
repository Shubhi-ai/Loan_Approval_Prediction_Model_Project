# Loan Approval Prediction Using Machine Learning

## Project Overview

This project predicts whether a loan application will be approved or rejected based on applicant information such as:

- Annual Income
- Loan Amount
- Loan Term
- CIBIL Score
- Education
- Employment Status
- Assets
- Number of Dependents

The goal is to assist financial institutions in making faster and more accurate loan approval decisions.

---

## Dataset Information

Rows: 4269

Columns: 13

Target Variable:
- loan_status

Features:
- no_of_dependents
- education
- self_employed
- income_annum
- loan_amount
- loan_term
- cibil_score
- residential_assets_value
- commercial_assets_value
- luxury_assets_value
- bank_asset_value

---

## Exploratory Data Analysis

Key Findings:

- Higher CIBIL scores strongly increase approval chances.
- Higher annual income improves approval probability.
- Asset values positively influence loan approval.
- Education and self-employment status have minimal impact.

---

## Machine Learning Models

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 90.51% |
| Decision Tree | 97.78% |
| Random Forest | 97.78% |

---

## Best Model

Random Forest Classifier

Reasons:
- High Accuracy
- Reduced Overfitting
- Better Generalization

---

## Feature Importance

Top Features:

1. CIBIL Score
2. Loan Term
3. Loan Amount
4. Residential Asset Value
5. Annual Income

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Installation

```bash
pip install -r requirements.txt
