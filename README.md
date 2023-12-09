# Final_Project_DATA1030
Predicting the Price of an S&P500 Stock

This repository contains the comprehensive work of my final project for the Hands-on Data Science course. It encompasses all the data utilized, alongside the figures generated and the outcomes achieved. The project involved data engineering, preprocessing, evaluation of various machine learning models, and hyperparameter tuning to identify the most effective model. The primary goal was to develop a machine learning model capable of accurately predicting S&P 500 stock prices, leveraging historical stock prices, quarterly financial metrics from the preceding quarter, and the sector information of the respective industries. The dataset spans the years 2012 to 2016 and looks at the stock prices of companies in the S&P500 in that period.

The various datasets employed in this project are conveniently stored in the 'Data' directory. To enhance data visualization and effectively present my findings, I have crafted numerous graphs and tables, all of which are housed in the 'Figures' directory. This project entailed rigorous testing of six distinct machine learning models, each undergoing meticulous hyperparameter tuning. The optimally tuned version of each model, representing the best performance achieved, is archived in the 'Results' directory. This directory also includes a comprehensive summary of the average RMSE scores for the different machine learning models, as well as the standard deviation of the average RMSE, providing a measure of their predictive accuracy.

In this project, I used five different machine-learning models to predict future stock prices. Among them, the Ridge Regression model emerged as the most accurate for forecasting stock prices, achieving the lowest average Root Mean Squared Error (RMSE) of 2.35 dollars. This figure suggests that the Ridge Regression Model predicts the price of a stock within a +/- 2.35 dollars range from the real stock price. The predictions made by the Ridge Regression Model with tuned hyperparameters are saved in the 'Data' directory  under 'y_pred_ridge'. 

The software, and their respective versions, that I used to code for this project are:
- Python: 3.11.4
- NumPy: 1.24.3
- Matplotlib: 3.7.1
- Scikit-learn: 1.3.0
- Pandas: 1.5.3
- XGBoost: 2.0.1
- SHAP: 0.43.0
- Seaborn: 0.12.2
