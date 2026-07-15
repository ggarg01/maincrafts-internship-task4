# Titanic Dataset Visualization Dashboard

### Maincrafts Data Science & Analytics Internship - Task 4

## Project Overview

This project creates a mini visualization dashboard using the Titanic dataset. The task focuses on data cleaning, feature engineering, exploratory data analysis (EDA), and creating multiple visualizations to communicate important insights about passenger survival.

## Tasks Completed

### Data Exploration and Cleaning

* Loaded the Titanic dataset using Pandas.
* Examined the dataset structure, columns, and missing values.
* Filled missing values in the Age column using the median.
* Filled missing values in the Embarked column using the mode.
* Removed the Cabin column due to a large number of missing values.
* Created new features including Family Size and Age Group for better analysis.

### Data Analysis

* Explored the distribution of passenger ages.
* Analyzed survival rates by gender.
* Compared fare distributions across passenger classes.
* Examined the relationship between passenger age and ticket fare.
* Explored correlations between numerical features.
* Compared survival rates by passenger class for male and female passengers.

### Visualizations

* Histogram of passenger age distribution.
* Bar chart of survival rate by gender.
* Box plot of fare distribution by passenger class.
* Scatter plot of age vs. fare.
* Correlation heatmap of numerical features.
* Catplot showing survival rate by passenger class and gender.

## Key Findings

* Most passengers were young adults between 20 and 40 years of age.
* Female passengers had a significantly higher survival rate than male passengers.
* First-class passengers generally paid higher fares and had better survival chances.
* No strong relationship was observed between passenger age and ticket fare.
* The correlation heatmap highlighted relationships between passenger class, fare, and survival.
* Female passengers consistently showed higher survival rates across all passenger classes.

## Files Included

* task4_titanic.ipynb – Jupyter Notebook containing the complete dashboard, analysis, visualizations, and observations.
* Titanic.csv – Titanic dataset used for the analysis.

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook (VS Code)
