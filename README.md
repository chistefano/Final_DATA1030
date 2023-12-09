# Final_Project_DATA1030
Predicting the Price of an S&P500 Stock

This repository contains the comprehensive work of my final project for the Hands-on Data Science course. It encompasses all the data utilized, alongside the figures generated and the outcomes achieved. The project involved data engineering, preprocessing, evaluation of various machine learning models, and hyperparameter tuning to identify the most effective model. The primary goal was to develop a machine learning model capable of accurately predicting S&P 500 stock prices, leveraging historical stock prices, quarterly financial metrics from the preceding quarter, and the sector information of the respective industries. The dataset spans the years 2012 to 2016 and looks at the stock prices of companies in the S&P500 in that period.

The various datasets employed in this project are conveniently stored in the 'Data' directory. To enhance data visualization and effectively present my findings, I have crafted numerous graphs and tables, all of which are housed in the 'Figures' directory. This project entailed rigorous testing of six distinct machine learning models, each undergoing meticulous hyperparameter tuning. The optimally tuned version of each model, representing the best performance achieved, is archived in the 'Results' directory. This directory also includes a comprehensive summary of the average RMSE scores for the different machine learning models, as well as the standard deviation of the average RMSE, providing a measure of their predictive accuracy.

In this project, I found that the best model for predicting the stock price was Ridge Regression. This model has an average Root Mean Squared Error of 2.35 dollars, with a standard deviation of 0.08. This means that the Ridge Regression model should be able to predict prices 99% of the time within +/- 2.14-2.56 dollars from the real price. The predictions made by this model are also saved in the Data file under 'y_pred'. 

The software, and their respective versions, that I used to code for this project are:
- Python: 3.11.4
- NumPy: 1.24.3
- Matplotlib: 3.7.1
- Scikit-learn: 1.3.0
- Pandas: 1.5.3
- XGBoost: 2.0.1
- SHAP: 0.43.0
- Seaborn: 0.12.2
