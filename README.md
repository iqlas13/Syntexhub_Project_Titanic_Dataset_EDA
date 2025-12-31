# Syntexhub_Project_Titanic_Dataset_EDA

# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)

## 📊 Week 3 – Project 1  
**SyntexHub Internship Project**

This project performs a comprehensive **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the factors that influenced passenger survival during the Titanic disaster.

The analysis focuses on data inspection, missing value handling, feature engineering, and visual exploration using Python data analysis and visualization libraries.

---

## 🎯 Project Objectives

- Load and inspect the Titanic dataset
- Analyze missing values and data types
- Perform data cleaning using statistical imputation
- Engineer meaningful features from raw data
- Analyze survival patterns based on gender, class, age, and family size
- Visualize insights using bar charts, heatmaps, KDE plots, and violin/box plots
- Prepare a clean dataset suitable for further machine learning tasks

---

## 📁 Dataset Information

- **Dataset Name:** Titanic – Machine Learning from Disaster  
- **Source:** Kaggle  
- **File Used:** `train.csv`  

The dataset contains passenger-level information such as age, gender, ticket class, fare, family details, and survival status.

---

## 🧹 Data Cleaning & Feature Engineering

The following preprocessing steps were performed:

- Missing values in **Age** were imputed using the median
- Missing values in **Embarked** were filled using the mode
- Cabin information was transformed into a binary feature (**HasCabin**)
- Passenger titles were extracted from names
- Family-related features (**FamilySize**, **FamilyGroup**) were created
- Redundant and high-cardinality columns were removed
- Categorical features were encoded using One-Hot Encoding

---

## 📊 Visualizations Included

- Missing Values Heatmap  
- Survival Rate by Passenger Class and Gender  
- Age Distribution by Survival Status (KDE Plot)  
- Feature Correlation Heatmap  
- Age vs Survival (Violin + Box Plot)  

All visualizations are saved as PNG files for documentation and reporting.

---

## 📝 Key Insights

- Female passengers had significantly higher survival rates than males
- First-class passengers showed much higher survival probabilities
- Younger passengers, especially children, had better survival chances
- Passengers traveling with small families survived more than those traveling alone
- Gender and socio-economic class were stronger predictors of survival than age alone

---

## 🧰 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

AUTHOR 
IQLAS THARANNUM

