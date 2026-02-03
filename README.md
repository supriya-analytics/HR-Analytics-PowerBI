## 📌 Project Overview
This project focuses on **cleaning, transforming, and analyzing messy HR Analytics data** using **Power BI and Power Query**.  
The goal is to demonstrate real-world data preparation skills before dashboard creation.

## 🛠 Tools Used
- Power BI Desktop
- Power Query Editor
- CSV Dataset (Messy HR Data – 1000 rows)

## 📂 Dataset
- File: `hr_analytics_messy_1000_rows.csv`
- Type: Messy / Raw HR data
- Issues included:
  - Missing values (Age, Salary, Contact Info)
  - Inconsistent text values (Gender, Performance)
  - Incorrect datatypes
  - Combined columns
  - Unnecessary columns

## 🔄 Data Transformation Steps
The following transformations were performed in **Power Query**:

1. Removed unwanted columns (Extra Column).
2. Fixed datatypes for Age, Salary, and Join Date.
3. Handled missing values:
   - Age filled using average value.
   - Salary cleaned and filled using median/average.
4. Standardized text values (Gender, Performance).
5. Split Contact Info into Phone Number and Email.
6. Created conditional columns:
   - Age Group (Below 30, 30–40, Above 40)
   - Salary Band (Low, Medium, High)
7. Created measures for KPIs such as:
   - Average Age
   - Average Salary
   - Attrition Rate

## 📊 Dashboard Visuals
The dashboard includes:
- Employee Count by Department
- Attrition Rate by Department
- Average Salary by Job Role
- Employee Distribution by Age Group
- Salary Band Distribution
- KPI Cards (Total Employees, Avg Age, Attrition Rate)
