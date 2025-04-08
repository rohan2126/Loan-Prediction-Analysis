# Loan Eligibility Prediction

Dream Housing Finance Company provides home loans across urban, semi-urban, and rural areas. The company aims to automate the loan eligibility process based on customer details provided in online application forms. This project builds a machine learning model to predict loan approval, helping the company identify eligible customers more efficiently.

## Problem Statement

This is a **supervised classification problem** where the goal is to predict whether a loan will be approved (`Loan_Status`) based on applicant data such as income, education, marital status, credit history, and more.

---

##  Dataset Information

The dataset contains the following features:

| Feature              | Description                                      |
|----------------------|--------------------------------------------------|
| Loan_ID              | Unique loan identifier                           |
| Gender               | Male / Female                                    |
| Married              | Marital status of the applicant (Yes / No)       |
| Dependents           | Number of dependents                             |
| Education            | Education level (Graduate / Under Graduate)      |
| Self_Employed        | Self-employment status (Yes / No)                |
| ApplicantIncome      | Income of the applicant                          |
| CoapplicantIncome    | Income of the co-applicant                       |
| LoanAmount           | Loan amount (in thousands)                       |
| Loan_Amount_Term     | Loan repayment term (in months)                  |
| Credit_History       | Credit history meets guidelines (1 = Yes, 0 = No)|
| Property_Area        | Area type (Urban / Semi-Urban / Rural)           |
| Loan_Status          | Loan approved (Y = Yes, N = No)                  |

**Dataset Link**: [Kaggle - Loan Prediction Dataset](https://www.kaggle.com/altruistdelhite04/loan-prediction-problem-dataset)

---

##  Libraries Used

- `pandas` – Data manipulation
- `matplotlib` – Data visualization
- `seaborn` – Statistical plots
- `scikit-learn` – Machine learning models and evaluation

---

##  Machine Learning Algorithms

The following classification models were implemented and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Extra Trees Classifier

---

##  Best Model Performance

The **Extra Trees Classifier** achieved the highest accuracy with a score of **81.00%** on the validation data.

---

## 📌 Project Highlights

- End-to-end ML pipeline: data cleaning, feature engineering, modeling, evaluation
- Classification report & confusion matrix for model performance
- Accuracy comparison of different classifiers
- Clean and modular code for scalability
