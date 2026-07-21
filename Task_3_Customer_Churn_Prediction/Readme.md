# 📊 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

Customer churn prediction is a Machine Learning classification problem that identifies whether a customer is likely to leave a company or continue using its services.

This project was developed as part of the **CodSoft Machine Learning Internship**.

The model analyzes customer banking information and predicts whether the customer will **churn** or **stay**.

---

## 🎯 Objective

To build a Machine Learning model that can accurately predict customer churn based on customer demographics and account details.

---

## 📂 Dataset

Dataset Used:

**Churn_Modelling.csv**

The dataset contains customer information such as:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Credit Card Status
- Active Membership
- Estimated Salary

Target Variable:

- Exited
  - 0 → Customer stays
  - 1 → Customer churns

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- ipywidgets

---

## 🔄 Project Workflow

### 1. Data Loading

Imported the customer churn dataset and analyzed the available features.

### 2. Data Preprocessing

Performed:

- Handling categorical variables
- Label Encoding
- Feature selection
- Data preparation for model training

### 3. Exploratory Data Analysis

Analyzed customer characteristics and relationships between features using visualization techniques.

### 4. Model Training

Trained a classification model:

### 🌲 Random Forest Classifier

Random Forest combines multiple decision trees to improve prediction accuracy and reduce overfitting.

---

## 🤖 Model Prediction

The trained model predicts:

- ✅ Customer Will Stay
- 🚨 Customer Will Churn

A manual prediction interface was created using **ipywidgets**, allowing users to enter customer details and receive instant predictions.

---

## 📊 Features Used for Prediction

| Feature | Description |
|---|---|
| CreditScore | Customer credit score |
| Geography | Customer location |
| Gender | Customer gender |
| Age | Customer age |
| Tenure | Years with bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products |
| HasCrCard | Credit card availability |
| IsActiveMember | Active membership status |
| EstimatedSalary | Customer salary |

---

## 🚀 How to Run

1. Clone this repository.
g
2. Install required libraries:

3. Open the Jupyter Notebook:

4. Run all cells.

5. Enter customer details in the prediction interface.

---

## 👩‍💻 Developed By

**S. Vahini**

B.Tech - Artificial Intelligence & Data Science

CodSoft Machine Learning Internship