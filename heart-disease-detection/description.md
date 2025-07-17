I created and compared a few machine learning models trained to detect the likelihood of heart disease based on a number of factors, eventually discovering that out of the four models I created, an XGBoost boosted BayesSearchCV trained to optimize F1 score performed the best overall.

Steps I took:
1. Loaded up dataset and performed initial analysis for general information, null values, etc.
2. Converted categorical data to numerical values using get_dummies()
3. Created train-test split
4. Created and scored a Random Forest model, a Decision Tree model, and two XGBoost optimized BayesSearchCV models, one focusing on F1 score and the other aiming to optimize the area under the ROC curve
5. Compared confusion matrices, finding that the F1 optimized model performed the best at identifying true positives and true negatives
6. Compared feature importances of each model, finding that oldpeak (degree of ST segment depression during exercise stress training), cholesterol levels, and max heart rate were consistently among the most important features, even with great variation in other features' importances
