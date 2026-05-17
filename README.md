# 🎓 Student Performance Data Cleaning & EDA

This project focuses on cleaning and exploring a student performance dataset to extract meaningful insights from academic data.

---

## 📌 Objective

The main goal of this project is to:
- Clean raw educational data
- Handle categorical variables
- Perform exploratory data analysis (EDA)
- Create a meaningful target variable for future modeling

---

## 📂 Dataset Information

The dataset contains student information including:

- Gender
- Race/Ethnicity
- Parental level of education
- Lunch type
- Test preparation course
- Math score
- Reading score
- Writing score

---

## 🧹 Data Cleaning Steps

- Checked and confirmed no missing values
- Checked and removed duplicate rows (if any)
- Ensured dataset consistency

---

## 🔧 Feature Engineering

A new feature was created:

### 📊 Average Score
Calculated using:
- Math score
- Reading score
- Writing score

---

### 🎯 Performance Category (Target Variable)

Based on average score:

- **Excellent** → 80 and above  
- **Average** → 60 to 79  
- **Poor** → below 60  

---

## 🔄 Encoding

- One-Hot Encoding applied to categorical variables:
  - Gender
  - Race/Ethnicity
  - Lunch
  - Test preparation course

- Ordinal encoding applied to:
  - Parental level of education

---

## 📊 Exploratory Data Analysis (EDA)

- Distribution of performance categories
- Score distribution analysis
- Correlation analysis
- Data visualization using histograms and count plots

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📌 Key Insights

- Student performance varies significantly based on test preparation
- Parental education level has an influence on scores
- Average score helps in simplifying performance classification

---

## 🚀 Future Work

- Apply machine learning models
- Build classification models for performance prediction
- Improve feature engineering

---

## 📁 Project Structure
