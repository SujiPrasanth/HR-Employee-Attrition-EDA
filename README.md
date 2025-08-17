# 📊 Employee Attrition Analysis (EDA Project)

## 📌 Project Overview
Employee attrition (employee turnover) is one of the major challenges faced by organizations.  
This project performs **Exploratory Data Analysis (EDA)** on an HR dataset to identify factors influencing attrition.  

We analyze the data using **Univariate, Bivariate, and Multivariate** techniques to uncover patterns and relationships between employee demographics, job roles, income, overtime, and attrition.

---

## 🎯 Objectives
The main objective of this project is to answer critical business questions such as:
- What factors contribute the most to employee attrition?
- How do age, monthly income, job role, and overtime affect attrition?
- Are there certain combinations of factors that increase the risk of employees leaving?

---

## 📂 Dataset
- The dataset contains employee demographic and job-related features.  
- Key columns: `Age`, `Attrition`, `MonthlyIncome`, `OverTime`, `Department`, `JobRole`, `DistanceFromHome`, `JobSatisfaction`, `Gender`, `WorkLifeBalance`.

---

## 🔍 EDA Questions & Analysis

### 🔹 **Univariate (1 variable)**
- What is the overall attrition rate?  
- What is the age distribution of employees?  
- How is monthly income distributed?  
- How many employees work overtime vs not?  
- What is the distribution of job roles and departments?  

### 🔹 **Bivariate (2 variables)**
- How does attrition vary with age?  
- Is attrition higher among employees with lower monthly income?  
- Does overtime strongly affect attrition?  
- How does attrition differ across departments and job roles?  
- Is there a relationship between job satisfaction and attrition?  
- Does distance from home influence attrition?  

### 🔹 **Multivariate (3+ variables)**
- Which combination of job role and department has the highest attrition?  
- Is attrition higher for employees who do overtime and have low work-life balance?  
- How does attrition differ across gender within each job role?  
- Do younger employees with low income have higher attrition compared to older, higher-income employees?  

---

## 📊 Visualizations
The analysis includes:
- Histograms & Bar plots (Age, Income, Job Role, Department distributions)  
- Boxplots & Violin plots (Attrition vs Age, Income, Distance)  
- Heatmaps (Correlation between features)  
- Grouped bar charts (Attrition by Job Role, Department, Overtime)  

---

## ⚙️ Tools & Libraries
- **Python** 🐍  
- **Pandas** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/HR-Employee-Attrition-EDA.git
