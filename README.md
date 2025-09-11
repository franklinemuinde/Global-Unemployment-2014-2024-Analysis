#Global Unemployment Analysis
##Overview

This project analyzes global unemployment trends across countries and regions from 2014 to 2024. Using structured datasets, the analysis highlights variations in unemployment rates by demographics (age, gender), geography, and time. The notebook combines data cleaning, exploratory analysis, and visualization to uncover meaningful insights.

##Objectives

Clean and preprocess global unemployment datasets.

Explore unemployment patterns by country, region, sex, and age group.

Identify countries with the highest and lowest unemployment rates.

Compare unemployment trends across years (2014–2024).

Visualize findings through clear, interpretable charts.

##Dataset

Source: Global unemployment dataset (2014–2024).

Features include:

country_name

region

sex

age_group / age_categories

Global unemployment rates (2014–2024).

##Methodology

###Data Cleaning

Removed duplicate header rows.

Handled missing values (e.g., Ukraine’s incomplete data).

Standardized column names for analysis.

###Exploratory Data Analysis (EDA)

Calculated average unemployment by country, year, and region.

Segmented data by gender and age categories.

Ranked countries based on unemployment performance.

###Visualization

Trend plots (2014–2024).

Regional comparisons.

Top/bottom 5 countries by unemployment rate.

##Key Findings

Countries with consistently low unemployment rates cluster in specific regions(Africa, Asia and Oceania).

Youth unemployment rates are significantly higher than adult rates in many countries.

Global unemployment has shown both regional disparities and temporal fluctuations due to the COVID-19 pandemic.

##Tools & Libraries

Python (Jupyter Notebook)

Libraries: pandas, numpy, matplotlib, seaborn, sqlite3, ipython-sql

##Outputs

Cleaned unemployment dataset ready for further research.

Statistical summaries and visual insights.

SQL-based queries for reproducible data exploration.
