# Task 5: Personal Loan Acceptance Prediction (Bank Marketing Dataset) 📈🏦

## 📌 Overview
This project is part of the **DevelopersHub Corporation – Data Science & Analytics Internship Program**.

The objective of this task is to predict whether a customer is likely to **accept a personal loan offer** based on their demographic and financial details. This is a real-world marketing problem where banks analyze customer behavior to improve loan campaign success rates.

This project includes data exploration, preprocessing, classification modeling, evaluation, and business insight extraction.

---

## 🎯 Objective
The main objectives of this task are:
- Perform basic exploration on features such as **age, job, and marital status**
- Clean and preprocess the dataset
- Train a classification model using:
  - Logistic Regression  
  - Decision Tree Classifier
- Evaluate the model using:
  - Accuracy Score  
  - Confusion Matrix  
- Analyze which customer groups are more likely to accept the loan offer

---

## 📂 Dataset Information
**Dataset Name:** Bank Marketing Dataset  
**Source:** UCI Machine Learning Repository / Kaggle  

The dataset contains customer information such as:
- `age`
- `job`
- `marital`
- `education`
- `balance`
- `housing`
- `loan`
- `contact`
- `duration`
- `campaign`
- `pdays`
- `previous`
- `poutcome`

### Target Variable
- **y**
  - `yes` → Customer accepted the loan offer
  - `no` → Customer rejected the loan offer

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
- Loaded dataset from CSV file using pandas.

### 2️⃣ Dataset Inspection
- Checked dataset structure and summary using:
  - `.shape`, `.columns`, `.head()`
  - `.info()`, `.describe()`

### 3️⃣ Exploratory Data Analysis (EDA)
EDA was performed on important customer features:
- Age Distribution (Histogram)
- Job vs Loan Acceptance (Countplot)
- Marital Status vs Loan Acceptance (Countplot)
- Education vs Loan Acceptance (Optional)

### 4️⃣ Data Preprocessing & Encoding
- Converted categorical features into numeric form using **Label Encoding**.
- Prepared the dataset for machine learning models.

### 5️⃣ Model Training
The dataset was split into training and testing sets (80/20 split).
Classification models used:
- Logistic Regression
- Decision Tree Classifier

### 6️⃣ Model Evaluation
Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

### 7️⃣ Business Insights Extraction
Grouped analysis was performed to identify which customer groups have higher loan acceptance rates, such as:
- Job categories
- Marital status groups
- Age group trends

---

## 📊 Results & Insights
- The dataset was successfully explored and prepared for machine learning.
- Visualizations showed that customer demographics strongly influence loan acceptance.
- Logistic Regression achieved good accuracy for prediction.
- Decision Tree model was also tested for comparison.
- Group analysis helped identify which customer segments are more likely to accept loan offers.

---

## 📌 Conclusion
This project demonstrates a complete classification workflow for predicting personal loan acceptance. By exploring customer attributes such as age, job, and marital status, and applying machine learning models, meaningful insights were extracted that can support bank marketing decisions. The results highlight how predictive analytics can help improve targeted marketing campaigns.

---

## 📁 Repository Structure
Task-5-Personal-Loan-Acceptance/
│── Task5_PersonalLoanAcceptance.ipynb
│── README.md
│── bank.csv


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

Run all cells to view the EDA graphs, model training results, and evaluation metrics.

📌 Internship Task Reference

This task is part of the Data Science & Analytics Internship Tasks assigned by DevelopersHub Corporation.

👤 Author

Muhammad Arsalan Zahid
Data Science & Analytics Intern
DevelopersHub Corporation
