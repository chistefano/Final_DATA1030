# Final_DATA1030
Predicting S&P500 Stock Prices

This repository contains the work pertinent to my final project for my Hands-on Data Science class. This repository contains all the data used for this project, as well as figures created and the results I obtained after engineering the data, preprocessing the data, and evaluating different machine learning models to determine the best  one, as well as hyperparameter tuning. The aim of this project was to find a machine learning model that could accurately predict S&P500 stock prices through the use of previous stock prices and quarterly financial metrics from the previous quarter as ell as the sector of the stock the industry operated in. 

In this project, I created graphs and tables to better visualize the data and my findings, which I saved in the 'Figures' directory. 

I tested six different machine learning models and determined that the best one at predicting the stock price was Ridge Regression. This model has an average Root Mean Squared Error of 
2.35 dollars, with a standard deviation of 0.08. This means that the Ridge Regression model should be able to predict prices 99% of the time with an error within the range of around 2.14-2.56 dollars.


The software, and their respective versions, that I used to code for this project are:
- Python: 3.11.4
- NumPy: 1.24.3
- Matplotlib: 3.7.1
- Scikit-learn: 1.3.0
- Pandas: 1.5.3
- XGBoost: 2.0.1
- SHAP: 0.43.0
- Seaborn: 0.12.2
