# Regression task

Testing the covid-19 dataset with the following algorithms Linear Regressor, Decision Tree Regressor, and Random Forest Regressor.

We used the RMSE metric to assess how well the model performed.

In RandomForestRegressor, we perform the feature selection to improve the model further; we serve the adjustment of the hyperparameters using GridSearchCV and using cross-validation to ensure that we will use all data for training and testing.

The best Regressor for this task was RandomForestRegressor.

We're still investigating the Support Vector Regressor's (SVR) performance, but it didn't do well.
