# Task 4: Predicting Insurance Claim Amounts (Medical Insurance Charges Prediction) 🏥📊

## 📌 Overview
This project is part of the **DevelopersHub Corporation – Data Science & Analytics Internship Program**.

The goal of this task is to build a **Regression Model** that predicts the **medical insurance charges** (claim amount) based on personal information such as age, BMI, smoking status, and other attributes.

This project demonstrates a complete workflow including data loading, exploratory data analysis (EDA), feature encoding, model training, and evaluation.

---

## 🎯 Objective
The main objectives of this task are:
- Load and explore the Medical Insurance dataset
- Visualize the impact of **Age**, **BMI**, and **Smoking Status** on insurance charges
- Train a **Linear Regression model** to predict insurance charges
- Evaluate the model using:
  - **MAE (Mean Absolute Error)**
  - **RMSE (Root Mean Squared Error)**

---

## 📂 Dataset Information
**Dataset Name:** Medical Cost Personal Dataset  
**Source:** Kaggle  

The dataset contains the following features:
- `age` → Age of the person
- `sex` → Gender (male/female)
- `bmi` → Body Mass Index
- `children` → Number of children/dependents
- `smoker` → Smoking status (yes/no)
- `region` → Region of residence
- `charges` → Medical insurance cost (Target Variable)

### Target Variable
- **charges** → Insurance claim amount (medical cost)

---

## 🛠 Tools & Technologies Used
- **Python**
- **Jupyter Notebook / Google Colab**
- **pandas**
- **matplotlib**
- **seaborn**
- **scikit-learn**
- **NumPy**

---

## ⚙️ Project Workflow

### 1️⃣ Data Loading
- Dataset loaded using pandas from `insurance.csv`.

### 2️⃣ Dataset Inspection
- Checked dataset structure using:
  - `.shape`, `.columns`, `.head()`
  - `.info()`, `.describe()`
- Verified missing values using:
  - `.isnull().sum()`

### 3️⃣ Exploratory Data Analysis (EDA)
Visualizations were created to analyze the relationship between important features and insurance charges:
- **Age vs Charges** (Scatter Plot)
- **BMI vs Charges** (Scatter Plot)
- **Smoker vs Charges** (Box Plot)

### 4️⃣ Data Preprocessing
- Converted categorical columns into numerical format using **One-Hot Encoding** (`get_dummies`).

### 5️⃣ Model Training
- Split dataset into training and testing sets (80/20 split).
- Trained a **Linear Regression model**.

### 6️⃣ Model Evaluation
Model performance was evaluated using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**

---

## 📊 Results & Insights
- The dataset was clean and contained no missing values.
- EDA showed that:
  - Insurance charges increase with age.
  - Higher BMI values tend to result in higher charges.
  - Smoking status has a very strong impact on insurance charges.
- Linear Regression model successfully predicted insurance charges with measurable error metrics.

---

## 📌 Conclusion
This project successfully demonstrates how regression modeling can be used to predict medical insurance costs. After exploring the dataset through EDA, categorical variables were encoded and a Linear Regression model was trained. The model was evaluated using MAE and RMSE, providing a clear understanding of prediction accuracy.

This task improved practical skills in:
- Data exploration and visualization
- Feature encoding
- Regression modeling
- Model evaluation using error metrics

---

## 📁 Repository Structure
Task-4-Insurance-Charges-Prediction/
│── Task4_InsuranceChargesPrediction.ipynb
│── README.md
│── insurance.csv


---

## ▶️ How to Run This Project

### 1. Clone the repository
```bash
git clone https://github.com/MuhammaadArsalanZahid/DataScience-and-Analytics-Internship-Tasks.git
2. Install required libraries
pip install pandas matplotlib seaborn scikit-learn numpy
3. Run the notebook

Open the .ipynb file in:

Jupyter Notebook
OR
Google Colab

Run all cells to view results, graphs, and evaluation metrics.

📌 Internship Task Reference

This task is part of the Data Science & Analytics Internship Tasks assigned by DevelopersHub Corporation.

👤 Author

Muhammad Arsalan Zahid
Data Science & Analytics Intern
DevelopersHub Corporation
