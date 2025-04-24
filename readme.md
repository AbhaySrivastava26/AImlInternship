Titanic Dataset - Data Cleaning & Preprocessing

This project is part of an AI/ML internship task focused on learning how to clean and prepare real-world data for machine learning.

---

 Task Objective

The goal of this task is to clean and preprocess the Titanic dataset to make it ready for machine learning models. This includes handling missing data, encoding categorical values, normalizing numerical data, and removing outliers.

---

Dataset Used

We used a sample of the Titanic dataset containing the following features:

- PassengerId: ID of the passenger
- Survived: 0 = No, 1 = Yes
- Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name, Sex, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked

---

 Steps Performed

1.Loaded dataset using pandas
2.Explored data: checked for nulls and data types
3.Dropped Cabin column due to too many missing values
4.Filled missing:
   - Age with median value
   - Embarked with the most common value
5.Converted categorical data:
   - Sex (male → 0, female → 1)
   - Embarked (S → 0, C → 1, Q → 2)
6.Normalized Age and Fare using MinMaxScaler
7.Visualized and removed outliers in Fare
8.Saved the cleaned dataset as cleaned_titanic.csv

---

 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (for normalization)

---

 Output

- A clean, preprocessed dataset ready for ML.
- File: cleaned_titanic.csv

---
