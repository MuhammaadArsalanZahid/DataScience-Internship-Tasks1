# Task 3: Customer Churn Prediction (Bank Customers) 🏦📉

## 📌 Overview
This project is part of the **DevelopersHub Corporation – Data Science & Analytics Internship Program**.

The purpose of this task is to build a **Customer Churn Prediction model** that identifies whether a bank customer is likely to leave the bank or stay. Customer churn prediction is an important problem in the banking sector because it helps organizations retain valuable customers and improve business strategies.

This task includes data preprocessing, categorical encoding, model training, evaluation, and feature importance analysis.

---

## 🎯 Objective
The main objectives of this task are:
- Load and clean the churn dataset
- Prepare the dataset for machine learning
- Encode categorical features such as **Geography** and **Gender**
- Train a classification model to predict churn
- Evaluate model performance
- Analyze **feature importance** to identify key churn factors

---

## 📂 Dataset Information
**Dataset Name:** Churn Modelling Dataset  
**Source:** Kaggle  

The dataset contains customer details such as:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary

### Target Variable
- **Exited**
  - `1` → Customer Left the Bank (Churn)
  - `0` → Customer Stayed

---

## 🛠 Tools & Technologies Used
- **Python**
- **Jupyter Notebook / Google Colab**
- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Loaded the dataset using pandas from CSV file.

### 2️⃣ Data Cleaning & Preparation
- Checked missing values and dataset structure.
- Removed unnecessary columns:
  - `RowNumber`
  - `CustomerId`
  - `Surname`

### 3️⃣ Exploratory Data Analysis (EDA)
Basic EDA was performed to analyze churn patterns, including:
- Churn distribution (Exited count)
- Gender vs Churn
- Geography vs Churn

### 4️⃣ Categorical Encoding
Categorical variables were converted into numeric form:
- **Gender** encoded using Label Encoding
- **Geography** encoded using One-Hot Encoding

### 5️⃣ Model Training
The dataset was split into training and testing sets.
A classification model was trained using:
- **Random Forest Classifier** (recommended for feature importance)

### 6️⃣ Model Evaluation
Model performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 7️⃣ Feature Importance Analysis
Feature importance was extracted to identify the most influential factors affecting customer churn.

---

## 📊 Results & Insights
- The dataset was successfully cleaned and prepared.
- The trained model predicted churn with good accuracy.
- Feature importance analysis showed that variables like **Age, Balance, Credit Score, and Active Membership** play an important role in predicting churn.
- Visualizations helped identify churn trends based on geography and gender.

---

## 📌 Conclusion
This project demonstrates the complete workflow of a churn prediction system. The dataset was cleaned, categorical features were encoded, and a machine learning classification model was trained to predict customer churn. The model was evaluated using accuracy and confusion matrix. Feature importance analysis provided useful insights into which factors influence customer churn the most.

This task provides strong hands-on practice in:
- Data preprocessing
- Encoding categorical data
- Classification modeling
- Model evaluation
- Feature importance interpretation

---

## 📁 Repository Structure
Task-3-Customer-Churn-Prediction/
│── Task3_CustomerChurnPrediction.ipynb
│── README.md
│── Churn_Modelling.csv


---

## ▶️ How to Run This Project

### 1. Clone the repository
```bash
gitclone https://github.com/MuhammaadArsalanZahid/DataScience-and-Analytics-Internship-Tasks.git
2. Install required libraries
pip install pandas matplotlib seaborn scikit-learn
3. Run the notebook

Open the .ipynb file in:

Jupyter Notebook
OR
Google Colab

Run all cells step-by-step to see results.

📌 Internship Task Reference

This task is part of the Data Science & Analytics Internship Tasks assigned by DevelopersHub Corporation.

👤 Author

Muhammad Arsalan Zahid
Data Science & Analytics Intern
DevelopersHub Corporation
