# 🏦 AllLife Bank - Personal Loan Prediction

This repository contains a machine learning project developed for **AllLife Bank**, a U.S.-based financial institution, to help identify potential customers likely to purchase personal loans. 
The goal is to support the bank’s marketing department in targeting existing deposit (liability) customers and improve the conversion rate of future loan campaigns.

---

## 📌 Project Objective

AllLife Bank currently has a growing liability customer base (depositors), but a relatively small number of asset customers (borrowers). The bank aims to:

- Convert more liability customers into personal loan customers
- Retain them as depositors while cross-selling loans
- Increase loan uptake through targeted marketing

This project builds a **predictive model** (Binanary classification - Decision trees) to identify customers with a high likelihood of purchasing a personal loan.

---

## 🧠 Machine Learning Approach

- **Problem Type**: Binary Classification (Loan Purchased: Yes/No)
- **Modeling Techniques**:
  - Decision trees
- **Evaluation Metrics**:
  - Accuracy
  - Precision / Recall
  - F1 Score
  - Confusion matrix

## 📊 Dataset Overview

ID: Customer ID
  - Age: Customer’s age in completed years
  - Experience: #years of professional experience
  - Income: Annual income of the customer (in thousand dollars)
  - ZIP Code: Home Address ZIP code.
  - Family: the Family size of the customer
  - CCAvg: Average spending on credit cards per month (in thousand dollars)
  - Education: Education Level. 1: Undergrad; 2: Graduate;3: Advanced/Professional
  - Mortgage: Value of house mortgage if any. (in thousand dollars)
  - Personal_Loan: Did this customer accept the personal loan offered in the last campaign? (0: No, 1: Yes)
  - Securities_Account: Does the customer have securities account with the bank? (0: No, 1: Yes)
  - CD_Account: Does the customer have a certificate of deposit (CD) account with the bank? (0: No, 1: Yes)
  - Online: Do customers use internet banking facilities? (0: No, 1: Yes)
  - CreditCard: Does the customer use a credit card issued by any other Bank (excluding All life Bank)? (0: No, 1: Yes)

---

## 📁 How to use this project

  - The code for the project can be found in the attached load_uptake_predictor_model.ipynb

  - The dataset used in the project is in the attached Loan_Modelling.csv

  - Upload the file Loan_Modelling.csv to your own google drive.  Place it under a folder /content/drive/MyDrive/AIML/foodhub_order.csv or the folder of your choise.
  - Edit the notebook, modify the below code to map the file as input df = pd.read_csv('/content/drive/MyDrive/AIML/foodhub_order.csv')

