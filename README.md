The idea is to determine the age of abalone based on size and weight measurements of it's different parts.

Data Source:
https://archive.ics.uci.edu/ml/machine-learning-databases/abalone/abalone.data

Within this task I examined the data, prepared it for modeling, used in total 3 supervised learning algorythms:

    K Nearest Neighbours
    Linear Regression
    Least Absolute Shrinkage and Selection Operator.

I also used dimensional reduction and cross-validation.

In case of abalone dataset, Linear regression turns out to be the most accurate. PCA is a great way to speep up computation while retaining very good prediction score. Cross-validation is very useful for tuning hyperparameters.
