# Project Name
> ## Build A Regression Model Using Regularisation 


## Table of Contents
* [Project Brief](#project-brief)
* [Business Objectives](#business-objectives)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)


## Project Brief

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also need to determine the optimal value of lambda for ridge and lasso regression.

## Business Objectives

We are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Conclusions

- The model accuracy on Train and Test set for both ridge and lasso models are similar, we need to choose the simpler model.
- Because the Simple Linear Regression model is quite sophisticated, we would not consider it.
- Ridge Regression model is complex, so we would not consider that.
- Optimum value of lambda for Ridge Regression is 20. Optimum value of lambda for Lasso Regression is 0.0001.
- Because the Lasso Regression model is simpler, we would choose it because the majority of co-efficients are zero.

Set of columns which influnce the most for Sales Pricing are:

1. GrLivArea
2. OverallQual
3. MSZoning_RL
4. OverallCond
5. TotalBsmtSF
6. MSZoning_FV
7. GarageCars
8. 2ndFlrSF
9. MSZoning_RM
10. 1stFlrSF


## Technologies Used

- library - version 3.0


## Acknowledgements

- I would like to thank Upgrad and IIT-B for giving me this opportunity to work on building a regression model using regularisation 

## Contact
* [Bharat M](https://github.com/bharatmuniyappa/)
