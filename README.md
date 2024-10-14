# Loan Prediction - Automated Loan Eligibility Process

**Description**

This project is based on a dataset from the insurance domain, which is known for its heavy use of analytics and data science methods. The dataset provides a good example of working with insurance company data, the challenges involved, strategies used, and variables that influence outcomes.

The problem presented here is a classification task. The dataset contains 615 rows and 13 columns, each representing different customer information such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and others.

**Problem Statement**

The objective is to automate the loan eligibility process in real-time based on the customer's details provided while filling out an online application form. The company aims to streamline and target specific customer segments who are eligible for loans based on the given data.

The challenge is to create a model that can classify customers as eligible or ineligible for a loan based on factors such as:

- Gender
- Marital Status
- Education
- Number of Dependents
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

By automating this process, the company will be able to quickly identify and focus on eligible customers.

**Dataset Information**
 - **Rows:** 615
 - **Columns:** 13
 - **Type:** Classification Problem

The dataset can be downloaded from the following link: [Loan Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication)

**Features**

Here are the key columns of the dataset:
1. **Loan_ID:** Unique Loan Identifier
2. **Gender:** Male/Female
3. **Married:** Yes/No
4. **Dependents:** Number of dependents (0, 1, 2, 3+)
5. **Education:** Graduate/Not Graduate
6. **Self_Employed:** Yes/No
7. **ApplicantIncome:** Income of the applicant
8. **CoapplicantIncome:** Income of the coapplicant
9. **LoanAmount:** Loan amount in thousands
10. **Loan_Amount_Term:** Term of the loan in months
11. **Credit_History:** Credit history meets guidelines (1 for Yes, 0 for No)
12. **Property_Area:** Urban/Semiurban/Rural
13. **Loan_Status:** Loan approval status (Y for Yes, N for No)

**Objective**

To build a machine learning model that can predict whether a customer is eligible for a loan based on their information, thereby automating the loan eligibility process for the company.

**Installation**

To set up the project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies by running the following command:
````bash
pip install -r requirements.txt
````
3. Download the dataset from Kaggle using the link provided.
4. Preprocess the data (handle missing values, encode categorical variables).
5. Split the data into training and testing sets.
6. Train a classification model (e.g., Support Vector Machine, Decision Tree, Random Forest, etc.).
7. Evaluate the model's performance using metrics like accuracy.
8. Use the model to predict loan eligibility for new customer data.

**License**

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as per the terms of the MIT license. See the LICENSE file for details.
