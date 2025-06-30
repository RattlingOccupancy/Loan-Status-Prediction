# 🏦 Prediction of Loan Eligibility with the Help of Support Vector Machine (SVM)

This is the machine learning project, which seeks to determine the probability of loan eligibility by a loan applicant based on some personal details and financial characteristics. The training dataset is filled with demographic and loan-related attributes.

An entire ML pipeline (cleaning the data, label-encoding categorical attributes, training/testing division, and model assessment) is applied. This was also an excellent practice of binary classification of data based on real-world-like data.

---

## 💡 Problem Statement

Predict with given features of gender, level of education, income salary, number of dependants as well as property area whether or not an applicant will qualify a loan.

---

## 🔍 Algorithm Used

- **Support Vector Machine (SVM)** and linear kernel were selected because of its success on binary classification tasks.


---

---

## 📁 Dataset

- [Loan Eligibility Predication Dataset](https://www.kaggle.com/datasets/ninzaami/loan-predication)

---




## 🧠 Input Features
After preprocessing and label encoding, the following features were used:
- Gender (0 = Female, 1 = Male)
- Married (0 = No, 1 = Yes)
- Dependents (0, 1, 2, 4)
- Education (0 = Not Graduate, 1 = Graduate)
- Self_Employed (0 = No, 1 = Yes)
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area (0 = Rural, 1 = Semiurban, 2 = Urban)

