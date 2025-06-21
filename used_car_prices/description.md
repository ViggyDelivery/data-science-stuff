Created a machine learning model using Random Forest regression to predict the prices of used cars using a synthetically generated dataset.

Steps taken:
1. Load in dataset downloaded from Kaggle and get a brief understanding of the shape, layout, etc.
2. Change all NaN values within the Service History column to "Unknown".
3. Find and graph correlations between engine CC and price as well as make year and price.
4. Change categorical data to numeric data by manually mapping values to 0 and 1 and employing the Pandas get_dummies() function.
5. Create train and test datasets with a test size of 20%.
6. Sort X and y test datasets by index for future graphing use.
7. Create Random Forest regressor with 200 trees.
8. Predict values and score them, finding MAE of ~851, MSE of ~1149163, RMSE of ~1072, and R2 score of ~84.8%
9. Graph predicted and actual values, finding that the model struggles mostly with predicting extremely high and low prices, as is to be expected.
10. Graph residuals, noticing no residual trend, further indicating the model's overall effectiveness.
11. Graph the model's feature importances, finding that the two most important features for the model were engine CC at ~46.6% and make year at ~21.5%.
