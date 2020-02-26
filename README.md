# baseball_HR_linear_regression

## Project Goals

    - The goal of this project is to use linear regression models to predict total home runs for 2020. 
    In order to account for possible player injuries that may limit their plate appearances, 
    we engineered our dependent variable, Home Runs per Plate Appearance. 


## Data Sources

    - BaseballSavant.mlb.com
    - Baseball-Reference.com


## Data Summary

    - Using datasources mentioned above, we collected player statistics from the 2015 season through 2018. 
    Then we concatanated all four datasets into one master training set that we would use to train our regression model. 
    After cleaning the data, we had a total of 854 observations and 54 possible independent variables. 


## Tools

    - Pandas
    - SKLearn
    - Ridge, Lasso, Linear Regression Models
    - Standard Scaler
    - Polynomial Features

## Modeling Process

    - Selecting the most appropriate and impactful feature variables for our model consisted of several key processes.
        - A Correlation Heatmap to avoid using variables that are highly correlated with each other
        - Using scatter plots to show the relationship between potential independent variables and Home Runs
        - Using Ridge and Lasso with multiple lambda values
        - Transforming our training set into polynomial features
        - Linear Regression
        - StandardScaler
        - Trial and Error
        
## Final Model
    - Our best fitted model ended up being a basic linear regression with a lambda value of zero. 
    The primary metric that was used to determine the model with the best fit is RMSE (Root Mean Squared Error), which had a value of .6723 . 


## Results
    - 