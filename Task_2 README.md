# Task 2: Credit Risk Prediction (Loan Approval Classification) 💳📊

## 📌 Overview
This project is part of the **DevelopersHub Corporation – Data Science & Analytics Internship Program**.

The goal of this task is to build a **Credit Risk Prediction model** that predicts whether a loan applicant is likely to be approved or rejected based on applicant details such as income, education, loan amount, credit history, and other factors.

This task demonstrates the complete workflow of a machine learning classification project including data cleaning, exploratory data analysis (EDA), model training, and evaluation.

---

## 🎯 Objective
The main objectives of this task are:
- Load and explore the Loan Prediction dataset
- Handle missing values appropriately
- Perform Exploratory Data Analysis (EDA) using visualizations
- Train a classification model such as Logistic Regression / Decision Tree
- Evaluate model performance using Accuracy Score and Confusion Matrix

---

## 📂 Dataset Information
**Dataset Name:** Loan Prediction Dataset  
**Source:** Kaggle  

The dataset contains information about loan applicants including:

- Gender  
- Marital Status  
- Education  
- Applicant Income  
- Coapplicant Income  
- Loan Amount  
- Loan Amount Term  
- Credit History  
- Property Area  

### Target Variable
- **Loan_Status**
  - `Y` → Loan Approved
  - `N` → Loan Rejected

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
- Loaded dataset using pandas.

### 2️⃣ Data Inspection
- Checked dataset structure using:
  - `.shape`, `.columns`, `.head()`
  - `.info()`, `.describe()`

### 3️⃣ Data Cleaning
- Handled missing values using:
  - Mode for categorical features
  - Mean for numerical features

### 4️⃣ Exploratory Data Analysis (EDA)
Visualizations created:
- Loan Amount Distribution (Histogram)
- Applicant Income Distribution (Histogram)
- Education vs Loan Status (Countplot)
- Credit History vs Loan Status (Countplot)

### 5️⃣ Data Encoding
- Converted categorical features into numeric form using Label Encoding.

### 6️⃣ Model Training
- Split dataset into training and testing sets.
- Trained a **Logistic Regression** model.

### 7️⃣ Model Evaluation
Model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📊 Results & Insights
- Dataset was successfully cleaned and prepared for machine learning.
- EDA showed that features such as **Credit History** and **Income** strongly influence loan approval decisions.
- Logistic Regression provided good classification accuracy on the test dataset.
- Confusion matrix helped identify correct and incorrect predictions.

---

## 📌 Conclusion
This project successfully demonstrates how to build a credit risk prediction system using machine learning.  
The dataset was cleaned, analyzed through EDA, and used to train a classification model. The trained model was evaluated using accuracy and confusion matrix, showing how predictive analytics can assist in financial decision-making.

---

## 📁 Repository Structure
Task-2-Credit-Risk-Prediction/
│── Task2_CreditRiskPrediction.ipynb
│── README.md
│── train.csv


---

## ▶️ How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/MuhammaadArsalanZahid/DataScience-and-Analytics-Internship-Tasks.git
2. Install required libraries
pip install pandas matplotlib seaborn scikit-learn
3. Run the notebook

Open the .ipynb file in:

Jupyter Notebook
OR
Google Colab

Run all cells to see results.

📌 Internship Task Reference

This task is part of the Data Science & Analytics Internship Tasks assigned by DevelopersHub Corporation.

👤 Author

Muhammad Arsalan Zahid
Data Science & Analytics Intern
DevelopersHub Corporation
