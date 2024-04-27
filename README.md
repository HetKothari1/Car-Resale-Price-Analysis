# Car-Resale-Price-Analysis

### Project Overview
This project focuses on analyzing car resale data to understand the factors influencing the resale price of cars. The dataset contains various columns such as brand, mileage, price, and fuel type, which were used to build a linear regression model.

## Data Sources
accounts.csv - each record describes static characteristics of an account,

clients.csv  - each record describes characteristics of a client,

disp.csv - each record relates together a client with an account i.e. this relation describes the rights of clients to operate accounts,

order.csv - each record describes characteristics of a payment order,

transaction.csv - each record describes one transaction on an account,

loan.csv  - each record describes a loan granted for a given account,

card.csv  - each record describes a credit card issued to an account,

district.csv - each record describes demographic characteristics of a district.

## Tools
Python: Used for data cleaning, preprocessing, and building the linear regression model.

Pandas: Used for data manipulation and analysis.

NumPy: Used for numerical operations.

Matplotlib and Seaborn: Used for data visualization.

Scikit-learn: Used for building the linear regression model and evaluating its performance.

## Approach
Data Preprocessing: Cleaned the dataset to handle missing values, convert categorical variables and removed outliers to make distribution closer to normal distribution.

Exploratory Data Analysis (EDA): Conducted EDA to gain insights into the relationships between different features and the target variable. Used visualizations such as scatter plots, histograms, and box plots.

Model Building: Built a linear regression model using Scikit-learn to predict the resale price of cars.

Model Evaluation: Evaluated the model using metrics such as mean squared error (MSE) to assess its performance.

Prediction: Used the trained model to make predictions on the test dataset.

Results Analysis: Analyzed the results to determine the accuracy of the model in predicting the resale price of cars.

## Results
-The analysis provides a detailed understanding of client demographics, highlighting district-wise variations and trends.

-Insights into financial performance over time offer valuable strategic direction for the bank.

-Examination of account and card usage patterns identifies opportunities for service enhancement and product development.

-Identification of major expenses opens avenues for cost reduction and improved profitability.

-Analysis of the loan portfolio sheds light on lending patterns and client segments, enabling targeted marketing and risk management strategies.
