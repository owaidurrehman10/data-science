# 🩺 Insurance Cost Analysis & Prediction

This project explores the "insurance.csv" dataset to understand the factors influencing insurance charges and preprocessing  the data for further machine learning modeling.

## 📊 Exploratory Data Analysis (EDA)

 **Data Loading & Inspection**: Read the dataset using pandas and checked for missing/null values.
**Visualization**: Using subplots to visualize relationships between each features against "charges".
 **Statistical Analysis**: Compared mean charges across subcategories within each feature.
                           Determined that "sex" and "region" have minimal impact on "charges" .

## 🧹 Data Preprocessing
**Outlier Removal**: Applied the standard deviation method to detect and remove outliers from numerical features.
**Feature Selection**: the "sex" and "region" has very less impact on "charges" ,hence its better to drop them.
**Categorical Encoding**: Converted "smoker" column: "yes" → 1, "no" → 0 .
**Final Dataset**: Cleaned and transformed dataset ready for machine learning tasks.
