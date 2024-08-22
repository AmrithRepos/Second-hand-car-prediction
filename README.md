Project Overview
This project involves predicting car prices using a Linear Regression model. The dataset, sourced from CarDekho, includes various features related to car specifications, including fuel type, seller type, transmission type, and ownership history. The goal is to build and evaluate a model that can predict the selling price of cars based on these features.

Dataset
The dataset used in this project is named "CAR DETAILS FROM CAR DEKHO.csv". It contains information on:

Car name
Selling price
Fuel type
Seller type
Transmission type
Number of previous owners
Steps Performed
Data Loading and Exploration

Loaded the dataset using Pandas.
Explored the dataset to understand its structure and contents.
Checked for missing values.
Data Preprocessing

Encoded categorical variables (fuel type, seller type, transmission type, and owner type) into numerical values.
Dropped non-numeric columns that are not useful for modeling.
Data Splitting

Split the data into features (X) and target variable (y).
Further divided the data into training and testing sets using an 90-10 split.
Model Training

Trained a Linear Regression model on the training data.
Model Evaluation

Evaluated the model using R-squared error on the training data.
Visualized the performance by comparing actual vs. predicted prices for both training and testing data.
Results
R-squared Error: Measures how well the model's predictions match the actual data.

Visualization: Scatter plots comparing actual prices to predicted prices for both training and testing datasets.

Libraries Used
pandas: Data manipulation and analysis.
numpy: Numerical operations.
matplotlib and seaborn: Data visualization.
scikit-learn: Machine learning model building and evaluation.

Output:
![image](https://github.com/user-attachments/assets/30619051-0dfc-418b-82cc-7ae0b6dbcf33)
