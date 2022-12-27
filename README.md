# Surprise Housing - Sale Price Prediction
A US-based housing company named Surprise Housing has decided to enter the Australian market. 
The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. 
For the same purpose, the company has collected a data set from the sale of houses in Australia


## Business Goal
You are required to model the price of houses with the available independent variables. 
This model will then be used by the management to understand how exactly the prices vary with the variables. 
They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. 
Further, the model will be a good way for management to understand the pricing dynamics of a new market.

The company wants to know:

    1. Which variables are significant in predicting the price of a house

    2. How well those variables describe the price of a house.

## Summary

Initial model has been created without regularization and we observed Overfitting. Hence two more models have been designed
with Lasso and Ridge regularization approaches to overcome overfitting. Both Lasso and Ridge addressed the overfitting issue and
as expected Lasso provides much simpler and robust model.