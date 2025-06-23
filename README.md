# Diabetes Data Cleaning & Preprocessing

## 📌 Overview
This repository contains code for cleaning and preprocessing the **Pima Indians Diabetes Dataset** before applying machine learning models.

## 🛠️ Steps Performed
1. **Handled Missing Values**: Replaced zeros with `NaN` and imputed median.
2. **Standardized Features**: Scaled numerical data using `StandardScaler`.
3. **Removed Outliers**: Used IQR method to filter extreme values.
4. **Saved Cleaned Data**: Exported to `diabetes_clean.csv`.

## 📂 Files
- `diabetes.csv` (Original dataset)
- `data_cleaning.ipynb` (Jupyter Notebook with code)
- `diabetes_clean.csv` (Processed dataset)
- `README.md` (This documentation)

## 📊 Visualization
![Boxplot Before Cleaning](boxplot_before.png)  
*Outliers before removal*

![Boxplot After Cleaning](boxplot_after.png)  
*Data after outlier removal*

## 🚀 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/satwikkajjam/Basics-of-ML.git
