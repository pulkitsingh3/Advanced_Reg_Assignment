# Assignment Advanced Regression
> Outline a brief description of your project.


## Table of Contents
* [Problem Statement](#general-information)
* [Business Goal](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. The company wants to know 
- Which variables are significant in predicting the price of a house, and
- How well those variables describe the price of a house. 

## Business Goal
- Build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- Determine the optimal value of lambda for ridge and lasso regression.
- This model will then be used by the management to understand how exactly the prices vary with the variables
- They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns.
- The model will be a good way for the management to understand the pricing dynamics of a new market.

## Conclusions
- Stone Masonry Veneer Type has higher median Sales Price compared to other
- As Basement quality increases from Fair to Excellent, we see a corresponding increase in SalePrice.
- Houses that are partially completed have a higher median Saleprice compared to other categories. This might be because partially completed houses are usually new houses under construction.
- Increase in the overall quality has a direct positive effect on the sale price.
- Since the Test R2 is too low for linear regression, we  checked for some alternate methods of Regression like Ridge and Lasso.
- Optimim value of alpha is 10 for ridge regression.
- Optimim value of alpha is 0.001 for lasso regression.
