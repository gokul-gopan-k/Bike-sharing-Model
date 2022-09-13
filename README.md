# Bike sharing System modelling
>  Build a multiple linear regression model for the prediction of demand for shared bikes.A bike-sharing system is a service in which bikes are made available
   for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually
   computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the 
   same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information 
- The business problem 
  to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
- Dataset that is being used
  Bike sharing dataset.

 The main objective is find variables that are significant in predicting bike share demand and quantify how significant they are in prediction.
  A Linear Regression model is created for this objective. The coefficients of the model tell us how significant they are in predicting bike share demand.

Steps done
1) Data understanding and EDA
- identify target variable
- drop unncesssary and redundnat column
- EDA
2) Data preparation
- create dummy variables for categorical variables
- split into traina and test sets
-scaling
3) Model Building
  - create linear models using mix of automated and manual approach and select best model.
4) Validation of LR assumptions
5) Model Prediction
   - Predict on test data using model created
6) Model Evaluation
   - Evaluate model using R2 value and mean square error.


## Conclusions
1) Top three significant predictors of bike share demand are: temp, weathersit_light rain and yr with coefficinets 0.49, -0.28 and 0.23.
2) In total 8 there are variables that are significant in predicting the share bike demand which are:
   yr,temp ,windspeed ,season_spring ,season_winter ,mnth_July ,weathersit_light rain ,weathersit_mist.
   All these are signifiant with zero p value and VIF vale less than 5.
3) 3 variables are positively related with bike demand : yr,temp  ,season_winter 
   5 variables are negatively related with bike demand : windspeed ,season_spring, ,mnth_July ,weathersit_light rain ,weathersit_mist.


## Technologies Used
- Notebook - version 6.4.8
- pandas - It is used for data cleaning and analysis. 
- numpy - NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, and matrices like to get mean,median etc. 
- seaborn  - Seaborn is a library for making statistical graphics in Python.
- matplotlib.pyplot  - Matplotlib is a cross-platform, data visualization and graphical plotting library for Python.
- scikit-learn - machine learning library for the Python programming language. It features various classification, regression and clustering algorithms including support-vector machine.
- statsmodels - a Python package that provides a complement to scipy for statistical computations including descriptive statistics and estimation and inference for statistical models.
- scipy - open-source Python library used for scientific computing and technical computing. 

## Acknowledgements
- This project was inspired by Upgrade.
- References: google, stackoverflow, upgrad classes.


## Contact
Created by [https://github.com/gokul-gopan-k] - feel free to contact me!


