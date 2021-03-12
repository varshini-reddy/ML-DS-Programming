The goal of this exercise is to see how multi-collinearity can affect the predictions of a model.

For this, perform a multi-linear regression on the given dataset and compare the coefficients with those from simple linear regression of the individual predictors.

## **Instructions**

Read the dataset 'colinearity.csv' as a dataframe

For each of the predictor variable, create a linear regression model with the same response variable

Compute the coefficients for each model and store in a list.

Fit all predictors using a separate multi-linear regression object

Calculate the coefficients of each model

Compare the coefficients of the multi-linear regression model with those of the simple linear regression model.

DISCUSSION: Why do you think the coefficients change and what does it mean? 

## **Hints**

LinearRegression()


Returns a linear regression object from the sklearn library.

LinearRegression().coef_

This attribute returns the coefficient(s) of the linear regression object

sklearn.fit()

Fit linear model

df.reshape()

Return a ndarray with the values in the specified shape 

Note: This exercise is auto-graded and you can try multiple attempts. 