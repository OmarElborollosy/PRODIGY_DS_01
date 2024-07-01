

# Salary Prediction of Data Professions

## Overview

This project focuses on predicting salaries for data-related professions using a dataset containing information about professionals' designations, age, gender, and corresponding salaries. By analyzing this data, we gain insights into salary distributions, gender-based differences, and other relevant trends.

## Table of Contents

1. [Introduction](#introduction)
2. [Data](#data)
3. [Exploratory Data Analysis (EDA)](#eda)
4. [Results](#results)

## Introduction

In the field of data science, understanding salary distributions and factors affecting compensation is crucial. This project aims to explore the relationship between various features (such as gender and age) and salaries within the data professions domain.

## Data

- The dataset used for this analysis is named `Salary Prediction of Data Professions.csv`.
- Columns in the dataset:
    - `DESIGNATION`: Job title or role.
    - `AGE`: Age of the professional.
    - `SEX`: Gender (encoded as 0 for female and 1 for male).
    - `SALARY`: Salary in the corresponding profession.

## Exploratory Data Analysis (EDA)

1. **Data Loading and Cleaning**:
    - Loaded the dataset using Pandas.
    - Replaced infinite values with NaN.
    - Explored missing values in categorical variables.

2. **Gender Distribution**:
    - Visualized the distribution of gender using a bar chart.
    - Custom colors were used to distinguish between male and female.

3. **Age Distribution**:
    - Plotted a histogram to show the age distribution of employees.
    - Set x-axis limits to cover the entire age range.

4. **Average Salary by Gender**:
    - Calculated the average salary for each gender.
    - Created a bar chart with custom x-axis labels (Female and Male).

5. **Salary Distribution by Gender**:
    - Used a box plot to visualize the salary distribution for each gender.
    - Custom colors (skyblue and salmon) were applied.

## Results

- Gender disparities in salaries were evident.
- The EDA provided insights into salary distributions and potential outliers.
- Further analysis could explore additional factors impacting salaries.



