Task-5

# 🚀 Exploratory Data Analysis (EDA) on Titanic Dataset

## 📑 Project Overview
This project is part of the **Data Analyst Internship** program.  
The goal is to perform **Exploratory Data Analysis (EDA)** on the **Titanic dataset** to uncover key patterns, trends, and insights.

---

## 🛠 Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Information
- **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Rows**: 891
- **Columns**: 12
- Contains information about passengers such as age, gender, ticket class, fare, and survival status.

---

## 📊 EDA Steps
- Data Loading
- Data Cleaning (handling missing values)
- Univariate Analysis (Age, Sex, Pclass, Fare, etc.)
- Bivariate Analysis (Sex vs Survived, Pclass vs Survived)
- Multivariate Analysis (Correlation Heatmap, Pairplots)
- Visualizations using Matplotlib and Seaborn
- Summary of Insights

---

## 📝 Summary of Findings

### General Observations
- The dataset had missing values in `Age`, `Cabin`, and `Embarked`.
- The `Cabin` column had too many missing entries (~77%).

### Target Variable (Survived)
- Around **38%** of passengers survived.
- Around **62%** did not survive.

### Gender vs Survival
- **Females** had a much higher survival rate (~74%) than males (~19%).

### Passenger Class (Pclass) vs Survival
- 1st class passengers had the highest survival rate (~63%).
- 3rd class passengers had the lowest survival rate (~24%).

### Age Distribution
- Most passengers were between **20-40 years old**.
- Children (<10 years) had better chances of survival.

### Fare vs Survival
- Higher fares were linked to a higher survival probability.

### Embarked Port
- Most passengers embarked from Southampton (S).
- Passengers from Cherbourg (C) had a better survival rate.

### Correlation Heatmap
- `Fare` and `Pclass` showed moderate correlation.
- No major multicollinearity was detected.

---

## 📌 Key Insights
- **Gender** and **Passenger Class** were strong indicators of survival.
- **Children** had slightly higher chances of survival compared to adults.
- **Socio-economic status** played an important role in survival chances.

---

## 📦 Files Included
- `Titanic_EDA.ipynb` (Jupyter Notebook)
- `EDA_Report.pdf` (PDF version of the analysis)
- `train.csv` (dataset file, if allowed)
- `README.md` (this file)

---

## 🏁 Conclusion
EDA provided important insights about factors affecting survival on the Titanic.  
The visualizations made it easier to understand the distribution and relationships between variables.

---

# ✨ Thank you!

---
