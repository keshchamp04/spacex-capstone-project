# Data Wrangling 🔧

## Overview
This section focuses on cleaning and preparing the SpaceX launch dataset for further analysis and modeling.

## Objectives
- Handle missing and inconsistent data  
- Transform raw data into a structured format  
- Create features required for analysis and machine learning  

## Files Included
- data-wrangling.ipynb  
  → Performs data cleaning, preprocessing, and feature engineering on the collected dataset.

## Data Processing Steps
1. Loaded the dataset and inspected its structure  
2. Identified and handled missing values  
3. Analyzed different landing outcome categories  
4. Converted landing outcomes into binary labels:
   - Success = 1  
   - Failure = 0  
5. Created a new feature **`landing_class`** for classification  
6. Removed unnecessary columns and formatted data  

## Output
A cleaned and structured dataset ready for exploratory data analysis (EDA) and predictive modeling.

## Tools Used
- Python  
- Pandas  
- NumPy  
