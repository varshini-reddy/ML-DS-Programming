The aim of this exercise is to understand how to use multi regression. Here we will observe the difference in MSE for each model as the predictors change. 



## **Instructions:**

Read the file Advertisement.csv as a dataframe.

For each instance of the predictor combination, form a model. For example, if you have 2 predictors,  A and B, you will end up getting 3 models - one with only A, one with only B and one with both A and B.

Split the data into train and test sets

Compute the MSE of each model 

Print the Predictor - MSE value pair.



## **Hints:**

pd.read_csv(filename)


 Returns a pandas dataframe containing the data and labels from the file data

sklearn.preprocessing.normalize()

Scales input vectors individually to unit norm (vector length).

np.interp()

Returns one-dimensional linear interpolation

sklearn.train_test_split()

Splits the data into random train and test subsets

sklearn.LinearRegression()

LinearRegression fits a linear model

sklearn.fit()

Fits the linear model to the training data

sklearn.predict()

Predict using the linear model.



Note: This exercise is auto-graded and you can try multiple attempts. 