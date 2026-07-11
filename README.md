
# Loan Default Prediction using Machine Learning

## Project Overview

This project predicts whether a loan applicant is likely to repay or default on a loan using Machine Learning algorithms. It also includes Exploratory Data Analysis (EDA) and data visualizations to understand borrower behavior and identify the key factors influencing loan approval.

The project helps banks and financial institutions make informed lending decisions by identifying high-risk applicants.

---

## Problem Statement

Financial institutions receive thousands of loan applications every day. Manually evaluating each application is time-consuming and may lead to inconsistent decisions.

This project uses Machine Learning to classify applicants into:

- Safe Applicant (Likely to Repay)
- Risky Applicant (Likely to Default)

---

## Dataset Features

The dataset contains the following features:

- Loan_ID
- Gender
- Married
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (Target Variable)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Machine Learning Algorithms

- Logistic Regression
- Random Forest Classifier

---

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis (EDA)
5. Data Visualization
6. Encode Categorical Features
7. Split Dataset into Training and Testing Sets
8. Train Logistic Regression Model
9. Train Random Forest Model
10. Evaluate Model Performance
11. Predict Loan Status for New Applicants

---

## Exploratory Data Analysis (EDA)

The following visualizations were performed:

- Loan Status Count Plot
- Applicant Income Distribution
- Loan Amount Distribution
- Credit History vs Loan Status
- Property Area Count Plot
- Correlation Heatmap
- Confusion Matrix

---

## Model Evaluation

The models were evaluated using:

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score
- Classification Report

---

## Project Structure

```
Loan-Prediction/
│
├── Loan_Prediction.ipynb
├── loan_data_set.csv
├── README.md
```

---

## Business Use Case

Banks and financial institutions can use this model to:

- Identify high-risk applicants
- Reduce financial losses
- Speed up the loan approval process
- Improve decision-making using data-driven insights

---

## Future Enhancements

- Hyperparameter Tuning
- XGBoost Implementation
- Deployment using Streamlit or Flask
- Interactive Dashboard
- Model Explainability using SHAP

---

## Author

**Aksha Thurimella**

Aspiring Data Analyst | Machine Learning Enthusiast

GitHub: https://github.com/akshathurimella

---

## License

This project is developed for learning and educational purposes.
