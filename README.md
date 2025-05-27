

# Titanic Dataset Data Preprocessing:

## Overview
This project demonstrates the basic data cleaning and preprocessing steps for the Titanic dataset in preparation for machine learning.

## Steps Performed

1. **Imported and explored the dataset using Numpy,Pandas and Matplotlib**
2. **Handled missing values**
   - Filled `Age` with median
   - Filled `Embarked` with mode
   - Dropped `Cabin` due to excessive missing data
3. **Encoded categorical features**
   - Label encoded `Sex`
   - One-hot encoded `Embarked`
   - Dropped `Name`, `Ticket`, and `Cabin`
4. **Standardized numerical features**
   - Standardized `Age` and `Fare` using `StandardScaler`
5. **Visualized and removed outliers**
   - Used boxplots to visualize
   - Removed outliers using the IQR(Inter-Quartile Range)  method
6. **Created Cleaned CSV file for Task 2**
   - Using to_csv()

## Result
The dataset is now cleaned, encoded, standardized, and free of major outliers—ready for analysis or machine learning.

---

**Note:**  
For details, see the code and comments in the notebook/script.
