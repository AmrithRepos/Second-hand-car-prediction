<br><h2>Project Overview</h2></br>
<br><p>This project involves predicting car prices using a Linear Regression model. The dataset, sourced from CarDekho, includes various features related to car specifications, including fuel type, seller type, transmission type, and ownership history. The goal is to build and evaluate a model that can predict the selling price of cars based on these features.</p></br>

<br>Dataset</br>
<p><br>The dataset used in this project is named "Second_Hand_Car.csv". It contains information on:</p><br>

<li>Car name</li>
<li>Selling price</li>
<li>Fuel type</li>
<li>Seller type</li>
<li>Transmission type</li>
<li>Number of previous owners</li>

<br><h3>Steps Performed</h3><br>
<br>1.Data Loading and Exploration</br>
<br>2.Loaded the dataset using Pandas.</br>
<br>3.Explored the dataset to understand its structure and contents.</br>
<br>4.Checked for missing values.</br>
<br>5.Data Preprocessing<br>
<br>6.Encoded categorical variables (fuel type, seller type, transmission type, and owner type) into numerical values.</br>
<br>7.Dropped non-numeric columns that are not useful for modeling.</br>
<br>8.Data Splitting</br>
<br>9.Split the data into features (X) and target variable (y).</br>
<br>10.Further divided the data into training and testing sets using an 90-10 split.</br>
<br>11.Model Training</br>
<br>12.Trained a Linear Regression model on the training data.</br>
<br>13.Model Evaluation</br>
<br>14.Evaluated the model using R-squared error on the training data.</br>
<br>15.Visualized the performance by comparing actual vs. predicted prices for both training and testing data.</br>

<p><h3>Results:</h3></p>
R-squared Error: Measures how well the model's predictions match the actual data.

Visualization: Scatter plots comparing actual prices to predicted prices for both training and testing datasets.

<p><h3>Libraries Used</h3></p>
</li>pandas: Data manipulation and analysis.</li>
<li>numpy: Numerical operations.</li>
<li>matplotlib and seaborn: Data visualization.</li>
<li>scikit-learn: Machine learning model building and evaluation.</li>

Output:
![image](https://github.com/user-attachments/assets/30619051-0dfc-418b-82cc-7ae0b6dbcf33)
