# 📊 Machine Learning Fundamentals & Credit Risk Modeling

This repository contains my learning-based project on Machine Learning fundamentals,
focusing on real-world evaluation metrics, imbalanced datasets, statistics,
and credit risk modeling used in banking.

---

## 🎯 Project Goals

- Understand why accuracy fails for imbalanced datasets
- Learn classification and regression metrics
- Apply statistical reasoning in ML
- Study multicollinearity and feature dependency
- Understand credit risk concepts used by banks

---

## 🧠 Topics Covered

### 1. Classification Metrics

- Accuracy
- Precision
- Recall
- F1-Score (Harmonic Mean of Precision and Recall)

High accuracy does not always mean a good model,
especially in imbalanced datasets.

---

### 2. Imbalanced Dataset Problem

Example: Terrorist vs Non-Terrorist classification

- Dataset is highly imbalanced
- Model shows 98% accuracy
- Recall for minority class is 0%

This proves accuracy alone is misleading.
F1-Score and Recall are more reliable metrics.

---

### 3. Regression Metrics

- MAE (Mean Absolute Error)
- MSE (Mean Squared Error)
- RMSE (Root Mean Squared Error)
- MAPE (Mean Absolute Percentage Error)
- R² Score

Formula:
```
R² = 1 - (SSR / SST)
```

---

### 4. Train vs Test Accuracy

- Checking only training accuracy gives false confidence
- Always evaluate both training and testing performance

---

### 5. Hypothesis Testing

- Null Hypothesis (H₀)
- Alternate Hypothesis (H₁)
- Significance Level (α)
- p-value interpretation

Decision rule:
- p-value ≤ α → Reject H₀
- p-value > α → Fail to Reject H₀

---

### 6. Multicollinearity (VIF)

Formula:
```
VIF = 1 / (1 - R²)
```

| VIF Value | Interpretation |
|-----------|----------------|
| 1         | No multicollinearity |
| 1–5       | Low |
| 5–10      | Moderate |
| >10       | High |

---

## 🏦 Credit Risk Modeling

### Assets

- Housing Loan
- Personal Loan
- Vehicle Loan
- Education Loan
- Credit Card Loan

### Liabilities

- Savings Account
- Current Account
- Fixed Deposit
- Recurring Deposit

---

### Key Credit Risk Terms

- **NPA**: Loan with delayed repayment
- **Disbursed Amount**: Total loan given
- **OSP**: Outstanding Principal
- **DPD**: Days Past Due
- **PAR**: Portfolio at Risk

---

### Loan Classification by DPD

| DPD Range | Account Status |
|-----------|----------------|
| 0         | NDA (Timely Paid) |
| 1–30      | SMA-1 |
| 31–60     | SMA-2 |
| 61–90     | SMA-3 |
| 91–180    | NPA |
| >180      | Written-Off |

---

## 🛠 Tools & Skills

- Python
- Machine Learning
- Statistics
- Banking Domain Knowledge

---

## 👤 Author

**Ankan Bera**  
Master’s Student – Data Science & AI
