The aim of this exercise is to try to come up with a simple logistic regression model using the sklearn package.

Dataset Description:

The dataset used here is called the Iris dataset. This dataset has several features such as sepal length, sepal width based on which we predict which of the iris species that particular flower belongs to.

## **Instructions:**

Read the IRIS.csv file into a pandas dataframe.

Assign the predictor and response variables. Remember the aim is to predict the iris species

Standardise the predictor variable.

Split the dataset into train and validation sets, with 80% of the data for training

Fit a logistic regression model to the dataset

Compute and print the train and validation accuracy

Perform 10 fold cross-validation. Compute and print the accuracy

## **Hints:**

shuffle(df)

Shuffle arrays or sparse matrices in a consistent way

df.drop()

Drop specified labels from rows or columns.

sklearn.LogisticRegression()

Generates a Logistic Regression classifier

sklearn.standardize()

Standardize features by removing the mean and scaling to unit variance

sklearn.fit()

Fits the linear model to the training data

sklearn.predict()

Predict using the linear modReturns the coefficient of the predictors in the model.

sklearn.accuracy_score()

Accuracy classification score.

sklearn.cross_val_score()

Evaluate a score by cross-validation

numpy.mean()

Compute the mean along the specified axis.

numpy.std()

Compute the standard deviation along the specified axis.


Note: This exercise is auto-graded and you can try multiple attempts. 