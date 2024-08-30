# Employee-Turnover-Prediction

This project aims to predict employee turnover using data from an HR analytics dataset. The analysis identifies factors contributing to employee attrition and provides insights into generational, departmental, and demographic trends in employee turnover.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Analysis and Findings](#analysis-and-findings)
- [Data Preprocessing](#data-preprocessing)
- [Visualization](#visualization)
- [Technologies Used](#technologies-used)
- [Conclusion](#conclusion)

## Overview
Employee turnover is a significant challenge for many organizations, impacting productivity and increasing recruitment costs. This project uses machine learning techniques and exploratory data analysis to identify key factors influencing employee attrition. The primary goal is to assist HR departments in identifying at-risk employees and implementing strategies to reduce turnover.

## Dataset
The dataset used in this project is a CSV file named `HR_Analytics.csv`, which contains 1,470 entries and 35 columns. It includes various employee attributes such as age, department, job satisfaction, and attrition status.

### Key Features
- **Numerical Features:** Age, DailyRate, DistanceFromHome, MonthlyIncome, TotalWorkingYears, etc.
- **Categorical Features:** Attrition, BusinessTravel, Department, Education, JobRole, MaritalStatus, etc.

## Analysis and Findings
The analysis focused on identifying patterns and correlations between various factors and employee attrition. Key insights include:
- **Generational Distribution:** Millennials and Gen Z are the most likely to leave within the first few years of employment.
- **Attrition by Department:** The highest turnover rates are found in the Sales and Research & Development departments.
- **Factors Influencing Turnover:** Key factors include job satisfaction, work-life balance, and job role.

## Data Preprocessing
Data preprocessing steps included:
- Handling missing values and ensuring data integrity.
- Encoding categorical variables using one-hot encoding.
- Creating new features such as generational groupings based on age.

## Visualization
Several visualizations were created to support the analysis:
- **Distribution of Employees Across Generational Groups:** A bar plot showing the count of employees in different age groups.
- **Attrition by Gender and Education Field:** A count plot highlighting attrition trends across different education fields and gender.
- **Attrition by Work-Life Balance and Job Satisfaction:** Pie charts depicting the distribution of employee satisfaction metrics.

## Technologies Used
- **Python:** Data manipulation and analysis.
- **Pandas:** Data wrangling and manipulation.
- **Matplotlib & Seaborn:** Data visualization.
- **Jupyter Notebook:** For interactive coding and analysis.

## Conclusion
The analysis revealed significant patterns and factors contributing to employee turnover. Understanding these factors can help organizations devise targeted strategies to improve employee retention, particularly among younger generations and specific departments with higher turnover rates.
