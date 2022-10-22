# cross-validation
Cross Validation, Grid search
1. Load titanic.csv file.
2. Select 'Pclass','SibSp','Parch','Fare' columns as data. Select ‘Survived’ column as label.
3. Apply Logistic regression, KNN, SVM, Decision tree and random forest to classify the
data.
4. Use K-Fold Cross Validation to generalise the model accuracy.
5. Use grid search to identify the best possible SVM model from the following search space.
'C': [0.1, 1, 10, 100, 1000],
'gamma': [1, 0.1, 0.01, 0.001, 0.0001],
'kernel': ['rbf']
