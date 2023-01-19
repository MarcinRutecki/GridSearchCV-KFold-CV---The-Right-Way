# GridSearchCV-KFold-CV---The-Right-Way
Building the best possible model

Machine learning process involves selecting the model with best performance. However that is not always an easy task. The best model is not the one that gives accurate predictions on the training data, but the one which gives good predictions on the new data and avoids overfitting and underfitting.

We have two important factors to cover here:

- The performance on cross validation set.
- The choice of hyperparameters.
- Quite often, we can see cross validation used improperly, or the result of cross validation not being interpreted correctly.

We have very important questions here:

- Does cross-validation replace train-test split?
- Do we still need to take advantage of K-fold CV while performing GridSearchCV?
- What is the correct workflow for K-fold CV with GridsearchCV?
