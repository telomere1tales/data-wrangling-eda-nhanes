# Data Wrangling and Biostatistical Analysis - NHANES Dataset

## Overview
This project demonstrates a complete data wrangling and exploratory 
data analysis (EDA) pipeline applied to real-world clinical data from 
the National Health and Nutrition Examination Survey (NHANES).

## Methods
- **Missing data assessment** using the `naniar` package
- **Data cleaning:** removal of duplicates, variables with excessive 
missingness, and filtering of key clinical variables
- **Outlier detection** using the IQR method
- **Exploratory Data Analysis:** distribution plots, density plots 
by diabetes status
- **Table 1** of baseline characteristics using `tableone`
- **Correlation matrix** of clinical variables

## Key Findings
- Diabetes prevalence: 9.3% (consistent with US population estimates)
- Diabetic participants were significantly older (59.82 vs 38.85 years)
- Higher BMI and blood pressure in diabetic participants
- Age and systolic blood pressure showed the strongest correlation (r = 0.44)

## Tools & Packages
- R 4.5.3
- `NHANES`, `naniar`, `ggcorrplot`, `tableone`, `tidyverse`, `ggplot2`

## Files
- `data_wrangling_eda_nhanes.Rmd` — R Markdown source code
- `data_wrangling_eda_nhanes.html` — Full rendered report
