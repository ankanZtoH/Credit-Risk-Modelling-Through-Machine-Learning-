📊 Machine Learning Fundamentals & Credit Risk Modeling

This repository contains my learning-based machine learning project notes and implementations, covering classification metrics, regression metrics, imbalanced data handling, hypothesis testing, multicollinearity, and credit risk modeling concepts.
The project focuses on understanding real-world ML problems, not just model accuracy.

🚀 Project Objectives

Understand why accuracy alone is misleading in imbalanced datasets

Learn and apply classification & regression evaluation metrics

Explore credit risk modeling concepts used in banks

Study hypothesis testing for data-driven decision making

Analyze multicollinearity vs correlation using VIF

Build strong ML fundamentals for real-world applications

📌 Topics Covered
1️⃣ Classification Metrics

Implemented and explained using confusion matrices:

Accuracy

Precision

Recall

F1-score (Harmonic mean of Precision & Recall)

📌 Special focus on imbalanced datasets, where:

High accuracy ≠ good model

Recall & F1-score are more important

Example:
A terrorism detection problem where accuracy is 98%, but recall is 0% → dangerous model

2️⃣ Imbalanced Dataset Handling

Why accuracy fails

Importance of:

Recall (false negatives are costly)

F1-score

Conceptual use of:

Oversampling

Proper loss metric selection

3️⃣ Regression Metrics

Used for evaluating regression models:

MAE – Mean Absolute Error

MSE – Mean Squared Error

RMSE – Root Mean Squared Error

MAPE – Mean Absolute Percentage Error

R² Score

📌 Notes:

RMSE is scale-dependent

R² explains variance using:

R² = 1 − (SSR / SST)

4️⃣ Train vs Test Accuracy

Checking accuracy on training data only leads to underfitting illusion

Proper evaluation requires:

Training accuracy

Testing accuracy

5️⃣ Hypothesis Testing

Covered statistical testing fundamentals:

Null Hypothesis (H₀)

Alternate Hypothesis (H₁)

Significance Level (α)

p-value interpretation

Why we say “Fail to Reject H₀” instead of “Accept H₀”

📌 Tests discussed:

T-test → Categorical vs Numerical

Chi-square test → Categorical vs Categorical

ANOVA

6️⃣ Multicollinearity vs Correlation

Correlation checks linear relationship

Multicollinearity checks feature predictability from other features

📌 Used Variance Inflation Factor (VIF):

VIF = 1 / (1 − R²)

VIF Value	Interpretation
1	No multicollinearity
1 – 5	Low
5 – 10	Moderate
> 10	High
7️⃣ Credit Risk Modeling (Banking Use Case)
Assets

Housing Loan

Personal Loan

Vehicle Loan

Education Loan

Credit Card Loan

Liabilities

Savings Account

Current Account

Fixed Deposit

Recurring Deposit

8️⃣ Key Credit Risk Concepts
🔹 NPA (Non-Performing Asset)

Loan where repayment is delayed beyond acceptable limits.

🔹 Disbursed Amount

Total loan amount given to the customer.

🔹 OSP (Outstanding Principal)

Remaining unpaid loan amount.

🔹 DPD (Days Past Due)

Delay in repayment.

🔹 PAR (Portfolio at Risk)

Loans where DPD > 0.

9️⃣ Loan Classification by DPD
DPD Range	Account Status
0	NDA (Non-Delinquent Account)
1–30	SMA-1
31–60	SMA-2
61–90	SMA-3
91–180	NPA
>180	Written-off
🛠️ Tools & Skills Used

Python

Machine Learning fundamentals

Statistics & Probability

Banking domain knowledge

Model evaluation techniques

📚 Learning Outcome

This project helped me understand:

Why real ML problems are metric-driven

How domain knowledge (banking) influences model choice

The importance of statistical reasoning in ML

Why F1-score & Recall matter more than accuracy in critical systems

📌 Future Improvements

Implement models using real datasets

Apply SMOTE & cost-sensitive learning

Build an end-to-end credit risk prediction pipeline

Add visualization & model explainability
