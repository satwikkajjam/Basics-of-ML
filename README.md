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
- `tast1.ipynb` (Jupyter Notebook with code)
- `diabetes_clean.csv` (Processed dataset)
- `README.md` (This documentation)

## 📊 Visualization
![Boxplot Before Cleaning](<img width="1084" alt="Screenshot 2025-06-23 at 6 06 18 PM" src="https://github.com/user-attachments/assets/6a75c507-684c-4d1e-8b6b-14ac04293abb" />)
*Outliers before removal*

![Boxplot After Cleaning](<img width="1084" alt="Screenshot 2025-06-23 at 6 06 43 PM" src="https://github.com/user-attachments/assets/68973d1f-095c-497c-b852-8b306db51bc0" />)  
*Data after outlier removal*

## 🚀 How to Use
1. Clone the repo:
   ```bash
   git clone https://github.com/satwikkajjam/Basics-of-ML.git
