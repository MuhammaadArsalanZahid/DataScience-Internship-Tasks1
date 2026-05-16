# DataScience-Internship-Tasks1
# Task 1: Iris Dataset Exploration & Visualization 

## 📌 Overview
This project is part of the **DevelopersHub Corporation – Data Science & Analytics Internship Tasks**.  
The goal of this task is to explore and visualize the **Iris Dataset** using Python and perform basic Exploratory Data Analysis (EDA).

The Iris dataset is a well-known dataset that contains measurements of iris flowers and their species classification.

## 🎯 Objective
The main objectives of this task are:
- Load and inspect the Iris dataset using **pandas**
- Understand dataset structure using `.shape`, `.columns`, and `.head()`
- Perform basic data exploration and summarization
- Create visualizations to analyze patterns and distributions:
  - Scatter Plot
  - Histogram
  - Box Plot

## 📂 Dataset Information
**Dataset Name:** Iris Dataset  
**Total Rows:** 150  
**Total Columns:** 5  

### Features:
- `sepal_length`
- `sepal_width`
- `petal_length`
- `petal_width`
- `species`

The dataset contains three species of iris flowers:
- Setosa
- Versicolor
- Virginica

## 🛠 Tools & Technologies Used
- **Python**
- **Jupyter Notebook / Google Colab**
- **pandas**
- **matplotlib**
- **seaborn**

## ⚙️ Project Workflow
The task was completed using the following steps:

### 1. Data Loading
- The dataset was loaded using seaborn’s built-in dataset loader.

### 2. Dataset Inspection
- Structure and contents were checked using:
  - `.shape`
  - `.columns`
  - `.head()`
  - `.info()`
  - `.describe()`

### 3. Missing Values Check
- Checked for null values using:
  - `.isnull().sum()`

### 4. Exploratory Data Analysis (EDA)
The following visualizations were created:

#### ✅ Scatter Plot
- To analyze relationships between petal length and petal width
- Species-wise comparison using color separation

#### ✅ Histogram
- To analyze distribution of sepal length values

#### ✅ Box Plot
- To identify outliers and compare feature spread among species

---

## 📊 Results & Key Observations
- The dataset is clean with **no missing values**.
- Scatter plot shows that **Setosa is clearly separable** from other species.
- Petal-related features are more effective in distinguishing species.
- Box plots highlight noticeable variation in petal width across species.

---

## 📌 Conclusion
This project provided hands-on experience in dataset exploration, inspection, and visualization.  
Through EDA techniques, meaningful patterns were identified in the Iris dataset, demonstrating how visualization helps in understanding data trends before applying machine learning models.

## 📁 Repository Structure
Task-1-Iris-Dataset/
│── Task1_Iris_Exploration.ipynb
│── README.md

## ▶️ How to Run This Project
1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repo-name.git
Open the notebook in Jupyter Notebook or Google Colab.
Install required libraries (if not already installed):
pip install pandas matplotlib seaborn
Run all notebook cells.
📌 Internship Task Reference

This task is part of the Data Science & Analytics Internship Tasks provided by DevelopersHub Corporation.

👤 Author

Muhammad Arsalan Zahid
Data Science & Analytics Intern
DevelopersHub Corporation
