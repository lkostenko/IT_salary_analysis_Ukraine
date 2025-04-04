# IT Specialist Salary Analysis

This project analyzes a survey dataset of IT professionals' salaries in Ukraine, gathered in December 2022. The analysis uses **pandas** and **Python** to explore trends in salaries based on various factors, including job titles, years of experience, gender, English proficiency, and location. The project provides insights into salary distribution, job market trends, and how various factors affect IT salaries.

## Project Overview

In this project, we analyze a dataset that contains survey results from IT professionals across Ukraine. The dataset includes various columns such as job title, salary, years of experience, education level, and more. The goal is to provide insights on salary distributions and the impact of experience, job role, gender, and other factors on salaries.

## Data Description

The data comes from a salary survey of IT professionals. It contains information on:

- **Job Titles**: Various roles within the IT industry such as Software Engineer, QA Engineer, Product Analyst, and Business Analyst.
- **Salary**: Monthly salary in USD before and after taxes.
- **Experience Level**: Years of experience in the field.
- **Gender**: Gender of the individual (Male/Female).
- **Location**: Geographic location within Ukraine.
- **English Proficiency**: Level of English proficiency (Beginner, Intermediate, Upper-Intermediate, etc.).
- **Education Level**: Education status (Higher education, Secondary education, etc.).

The dataset is in CSV format and uses semicolons (`;`) as separators.

## Data

Download the dataset [2022_dec_raw.csv](https://drive.google.com/file/d/1blMFMgfxaPws21eDtt37myJnvX9YeIu4/view?usp=sharing)

## Analysis Details

In the analysis, the following steps were performed:

1. **Data Cleaning**: Missing values were handled, and columns were converted into appropriate data types (e.g., numerical columns such as salary and age).
2. **Data Transformation**: We transformed salary-related columns into numerical values and handled categorical data like job titles and English proficiency levels.
3. **Exploratory Data Analysis (EDA)**: 
    - Calculated the average salary for different roles and specializations.
    - Analyzed salary distribution by experience, gender, location, and education.
    - Visualized the correlation between job titles and salaries.
    - Compared salaries based on English proficiency and job titles.
4. **Findings**: The analysis includes insights into how salaries vary based on job role, experience, gender, and other factors.

## Findings

- **Salary by Job Title**: Senior, Architect, and Tech Lead roles tend to have the highest salaries, particularly in the Back-end and Full Stack specializations.
- **Gender Salary Gap**: Men generally have higher salaries compared to women across all job titles in the dataset.
- **Location**: Kyiv has the largest labor market with the highest diversity in salaries, followed by Lviv and Dnipro. Smaller cities like Ivano-Frankivsk and Vinnytsia tend to offer lower salaries but with less competition.
- **Impact of English Proficiency**: Higher levels of English proficiency correlate with higher salaries, especially for mid-level and senior roles.
- **Experience**: As experience increases, so do salaries, with significant jumps at the Senior and Tech Lead levels.
