The goal of this exercise is to fit linear regression and polynomial regression to the given data. Plot the fit curves of both the models along with the data and observe what the residuals tell us about the two fits. 

![img](/Users/Varshini/Desktop/ML-DS-Programming/MULTILINEAR REGRESSION/Multi_Poly_with_Residual/plot.png)

## **Instructions**

Read the poly.csv file into a dataframe

Fit a linear regression model on the entire data, using LinearRegression() object from sklearn library

Guesstimate the degree of the polynomial which would best fit the data

Fit a polynomial regression model on the computed PolynomialFeatures using LinearRegression() object from sklearn library

Plot the linear and polynomial model predictions along with the data

Compute the polynomial and linear model residuals using the formula below $\epsilon = y_i - \hat{y}$

Plot the histogram of the residuals and comment on your choice of the polynomial degree. 

## **Hints:**

df.head()


 Returns a pandas dataframe containing the data and labels from the file data

plt.subplots()

Create a figure and a set of subplots

sklearn.PolynomialFeatures()

Generates a new feature matrix consisting of all polynomial combinations of the features with degree less than or equal to the specified degree

sklearn.fit_transform()


Fits transformer to X and y with optional parameters fit_params and returns a transformed version of X

sklearn.LinearRegression()

LinearRegression fits a linear model

sklearn.fit()

Fits the linear model to the training data

sklearn.predict()

Predict using the linear model

plt.plot()

Plots x versus y as lines and/or markers

plt.axvline()


Add a vertical line across the axes

ax.hist()

Plots a histogram

Note: This exercise is auto-graded and you can try multiple attempts. 