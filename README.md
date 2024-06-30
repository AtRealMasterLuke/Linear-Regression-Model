# Linear-Regression-Model
This repo contains a simple example of using Linear Regression with the Scikit-learn library in Python.
The code demonstrates how to create a sample dataset, normalize the data, split it into training and test sets, train a Linear Regression model, and make predictions on the test data.
**Note**: This project is intended for learning purposes only, to help understand the basic concepts of Machine Learning in Python.
### Requirements
You'll need to install the following Python packages:
- numpy
- scikit-learn
# Code Explanation
The code performs the following steps:

-1 Imports: Necessary libraries are imported.
-2 Data Preparation: A sample dataset is created with 10 observations and 3 features.
-3 Normalization: Data is normalized using StandardScaler to improve model performance.
-4 Train-Test Split: The data is split into training and testing sets with a 60-40 ratio and a fixed random state for reproducibility.
-5 Model Training: The Linear Regression model is initialized (with no intercept term) and trained on the training set.
-6 Predictions: Predictions are made on the test set.
-7 Output: Results, including the training features, test features, test targets, and model predictions, are printed.
