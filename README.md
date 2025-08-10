# Regression-for-Car-Price-Prediction
**Description**
Create a regression model for predict the price of used car based on various attributes.

Your Goal: The goal of this competition is to predict the price of used cars based on various attributes.

**Evaluation**
Root Mean Squared Error (RMSE)
Submissions are scored on the root mean squared error.

**Modelling**
To determine the house price prediction interval, I conducted several experiments using different regression models, and obtained different results.

I worked on this project by trying several models, namely Ridge Regression Model, LightGBM Regressor, Catboost Regressor, Quantille Catboost, and Linear Regression Models. Here are the details of the Kaggle public score results from the regression model I did:

Linear Regression : 73697.46993
Ridge Regressor : 73383.75654
LightGBM : 73210.43760
Catboost : 73219.26119
Quantille Catboost : 73518.97872
Since the best score is calculated using the smallest score, based on this experiment, the most effective and best model out of all the models I tried is the LightGBM Regressor with a score of 73210.43760

Reference : https://www.kaggle.com/competitions/playground-series-s4e9/submissions
