# Decision Tree Classifier task: Bank Marketing - SkillCraftTechnology Internship

🌟 Project Overview

This project builds a Decision Tree Classifier to predict whether a bank customer will subscribe to a term deposit based on demographic and behavioral data.
The model uses the Bank Marketing Dataset from the UCI Machine Learning Repository.

📁 Dataset Information

Source: UCI Machine Learning Repository – Bank Marketing Dataset

File Used: bank-full.csv

Rows: 45,211

Columns: 17

Target Variable: y (subscription: yes/no)

🧪 Tools & Libraries

Python

Pandas

Matplotlib

Seaborn

Scikit-learn (DecisionTreeClassifier)

Jupyter Notebook

🧹 Data Cleaning & Preprocessing

Converted categorical variables to numeric using Label Encoding

Checked for null/missing values (dataset is clean)

Split data into training (80%) and test (20%) sets

📊 Exploratory Data Analysis (EDA)

Target distribution: Bar chart for subscription

Age distribution: Histogram

Balance vs Subscription: Box plot

Correlation between numeric features: Heatmap

🌳 Decision Tree Model

Classifier: DecisionTreeClassifier

Criterion: Gini

Max Depth: 5 (prevents overfitting)

Evaluation Metrics: Accuracy, Classification Report, Confusion Matrix

📈 Key Insights

Customer demographics and balance strongly influence subscription

Younger customers and those with higher balance are more likely to subscribe

Decision tree visualization reveals interpretable business rules

Tree depth tuning helps balance accuracy vs overfitting

✅ Conclusion

This project demonstrates:

Building an interpretable machine learning model

Handling categorical and numerical data

Performing exploratory data analysis to understand patterns

Visualizing results for business insights

📎 Reference

Bank Marketing Dataset – UCI Machine Learning Repository
https://archive.ics.uci.edu/dataset/222/bank+marketing
