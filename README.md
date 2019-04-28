# Car-price-predictor
Predicting the independent variables influencing car price using linear regression model.

Problem Statement:
This is a solution to programming assignment wherein you have to build a multiple linear regression model for the prediction of car prices.

Framework used: 
Jupyter Notebook

Problem description:
An automobile consulting company wants to understand the factors on which the pricing of cars depends. Specifically, they want to understand the factors affecting the pricing of cars in the American market, since those may be very different from the global market. 

  The consulting team wants to know:
  Which variables are significant in predicting the price of a car
  How well those variables describe the price of a car
  Based on various market surveys, the consulting firm has gathered a large dataset of different types of cars across the Americal market.
  
  
Solution:
The solution is provided in below steps.
1. Data import.
    Importing the data from the source.
2. Data cleansing.
    Removing nulls, checking values in categorical variables, remove columns with no business significance.
3. Data visualization.
    Use pairplot, correlation and box plots to check the relationship within numerical variables.
4. Data preparation
    Converting categorical into numerical variables.
5. Splitting data into train and test
    Splitting data into training and testing sets.
6. Rescaling the featuring
    Performing rescaling of feautes for faster modeling and easier gradient descent.
7. Building the model
    Building models with highly corelated variable.
    Performing multiple manual models to check the improvment in model.
8. Residual Analysis of the train data
    Check if the error terms are normally distributed.
9. Model prediction
    Predict on test data.
