# 🎓 Student Result Analysis & Prediction 📌

---

## 📖 Project Overview

This project analyzes student performance data and builds a machine learning model to predict scores in **Math, Reading, and Writing**.

It focuses on identifying how factors like **gender, parental education, study hours, and lifestyle** impact academic performance.

---

## 📂 Dataset

**Dataset used:** Expanded_data_with_more_features.csv
**Total records:** 30,641 students

### Features include:

* Gender
* Ethnic Group
* Parent Education
* Lunch Type
* Test Preparation
* Weekly Study Hours
* Scores (Math, Reading, Writing)

---

## 🧹 Data Preprocessing

* Removed unnecessary column (**Unnamed: 0**)
* Handled missing values
* Converted categorical data where required

### Checked dataset structure using:

* `.info()`
* `.describe()`
* `.isnull().sum()`

---

## 📊 Exploratory Data Analysis (EDA)

Performed detailed visualization using:

* Seaborn
* Matplotlib

---

## 📈 Visualizations

* Gender distribution
* Heatmaps of score averages
* Bar plots (**Gender vs Scores**)
* Correlation heatmap

---

## 🎯 Future Improvements

* Feature engineering
* Deploy using Streamlit
