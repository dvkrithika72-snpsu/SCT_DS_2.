SCT_DS_2 - Titanic Passenger Survival Analysis

Project Overview
This repository contains the implementation for Task 2 of the Data Science internship at SkillCraft Technology. The primary goal of this project is to perform Exploratory Data Analysis (EDA) to explore variables and identify patterns in the Titanic passenger dataset.

Task Details
Dataset: Titanic Dataset (Passenger survival data).

Objective: Clean the data and visualize the relationship between passenger characteristics (Gender, Class, Age) and survival rates.

Tools Used: Python, Pandas for data cleaning, Matplotlib, and Seaborn for multi-variate visualization.

Methodology
To uncover the "Women and Children First" social protocol, a multi-chart dashboard and correlation analysis were conducted.

Data Cleaning: Addressed 177 missing values in the Age column using median imputation and removed the Cabin column due to excessive missing data (70%+).

Feature Engineering: Removed unique identifiers like Name and Ticket to focus on statistical trends across the population.

Bivariate Analysis: Used bar plots to compare survival probabilities, revealing that Females (~74%) and 1st Class passengers (~63%) had the highest survival rates.

Statistical Analysis: A Correlation Heatmap was generated to mathematically confirm the strong relationship between Fare, Class, and Survival.

Visualization Preview : <img width="844" height="529" alt="output correlation heatmap " src="https://github.com/user-attachments/assets/a05f9aa6-7a9c-4890-9a16-7dceb6cd9707" />



<img width="1484" height="984" alt="output task 2" src="https://github.com/user-attachments/assets/20abe4c6-ac85-43e2-ab41-2d4c899a62fd" />



How to Run
Ensure Python and necessary libraries (pandas, matplotlib, seaborn) are installed.

Clone this repository.

Open task2.ipynb in VS Code or any Jupyter environment and run all cells.
