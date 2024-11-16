# Loan Approval Prediction Using Logistic Regression

## Overview
This project uses machine learning to predict loan approval decisions based on applicant data. By analyzing key features such as income, credit history, and loan amount, the project aims to provide insights into the factors influencing loan approval rates and build a classification model for accurate predictions.

---

## Key Features
- **Classification Model**: Built a logistic regression model to predict loan approval status.
- **Feature Importance**: Identified key factors affecting loan decisions.
- **Balanced Evaluation**: Handled imbalanced datasets to ensure fairness in model predictions.

---

## Dataset
- **Source**: Publicly available loan data.
- **Size**: ~600 entries, including approved and denied applications.
- **Features**:
  - ApplicantIncome
  - CoapplicantIncome
  - LoanAmount
  - Loan_Amount_Term
  - Credit_History
  - Gender, Married, Dependents, Education, Self_Employed
  - Loan_Status (Target Variable: 1 for Approved, 0 for Denied)
- **Preprocessing**:
  - Handled missing values using median and mode imputation.
  - Encoded categorical variables using one-hot encoding.
  - Normalized numerical features with Min-Max scaling.

---

## Methodology
1. **EDA**:
   - Explored distributions of applicant income, loan amounts, and credit history.
   - Visualized correlations between features and loan approval status.
2. **Feature Engineering**:
   - Created additional features, such as debt-to-income ratio.
   - Binned continuous variables (e.g., income ranges) for better interpretability.
3. **Modeling**:
   - Trained a logistic regression model on preprocessed data.
   - Tuned hyperparameters using Grid Search for optimal performance.
4. **Evaluation**:
   - Metrics: Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
   - Validated model using k-fold cross-validation.

---

## Key Insights
- **Credit History**: The most significant factor influencing loan approval, with applicants having a positive credit history showing a much higher approval rate.
- **Income**: Higher applicant and co-applicant incomes correlated positively with loan approvals.
- **Loan Amount**: Higher loan amounts slightly decreased the likelihood of approval.

---

## Technologies Used
- Python (Pandas, NumPy)
- Scikit-learn (Logistic Regression, Evaluation Metrics)
- Matplotlib and Seaborn for Visualizations

---

## Applications
- **Financial Institutions**: Automates the loan approval process, saving time and reducing biases.
- **Risk Management**: Helps identify high-risk applicants, allowing for targeted interventions.
- **Customer Insights**: Provides insights into approval likelihood based on financial history.

---

## Future Directions
1. Expand the dataset to include additional demographic and financial features.
2. Experiment with other classification models, such as Random Forest or Gradient Boosting.
3. Develop an interactive dashboard for real-time
