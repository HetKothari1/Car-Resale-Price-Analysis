# Car-Resale-Price-Analysis

## Project Overview
This project focuses on analyzing car resale data to understand the factors influencing the resale price of cars. The dataset contains various columns such as brand, mileage, price, and fuel type, which were used to build a linear regression model.

![car](https://github.com/HetKothari1/Car-Resale-Price-Analysis/assets/167286650/fa664bbc-85e2-4c91-a759-ac3723598687)

## Data Sources
car_resale.csv - contains all the details of the resold car

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
Mileage and brand were found to be the most influential factors affecting the resale price of cars.

The linear regression model performed well, with a low mean squared error (MSE) on the test dataset, indicating accurate predictions.

The model can help both buyers and sellers in the used car market by providing estimates of fair resale values based on key factors.

 Additional features such as car age, maintenance history, and market trends could further enhance the model's predictive power.
