# Advanced-Linea-Regression-House-Price-Prediction-Assignment
> You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.. 

## General Information

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file.  Company wants :
- Which variables are significant in predicting the price of a house.
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions

- Using Lasso method is have slightly less mean square error. Also, since Lasso helps in feature reduction, Lasso is recommended to use.
- Hence based on Lasso, the factors generally affect the price are the Zoning Classification, Neighborhood, GrLivArea, Overall Quality, BsmtExposure, HouseStyle. Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.


## Technologies Used

- Python: version 3.x
- Pandas: version 1.3.4
- Seaborn: version 0.12.2
- Matplotlib: version 3.5.3
- Numpy: version 1.21.6
- Sklearn: version 1.x
- Statsmodels: version 0.15.0