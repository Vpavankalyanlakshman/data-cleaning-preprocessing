# Task 1: Data Cleaning & Preprocessing

## Objective
Clean and prepare raw Titanic dataset for Machine Learning.

## Dataset
Titanic Dataset from Kaggle

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed
1. Imported dataset and explored nulls and data types
2. Handled missing values (Age→median, Embarked→mode, Cabin→dropped)
3. Encoded categorical features (Label + One-Hot Encoding)
4. Normalized numerical features using StandardScaler
5. Visualized and removed outliers using Boxplot + IQR method

## Result
- Original Shape: (891, 12)
- Final Clean Shape: (577, 9)
