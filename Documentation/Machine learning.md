**Machine Learning Models Used:**

1) Logistic Regression

2) Logistic Regression using 10 folds Grid Search Cross Validation at various regularization strengths and liblinear solver

3) Logistic Regression using 10 folds Grid Search Cross Validation at various regularization strengths and saga solver

4) Logistic Regression using 10 folds Grid Search Cross Validation at various regularization strengths and saga solver and with using principle component analysis

5) Decision Tree Classifier

6) Decision Tree with Grid Search

7) Support Vector Machine

8) K-Nearest Neighbours

9) Ensemble Methods

10) Adaboost Model

**Conclusions:**

1) The classifier's efficiency to identify the model is determined by the Area Under the Curve (AUC) Score.

2) Initial AUC score using logistic regression model is 58 percent, that implies that the model is 58 % efficient in determining the target classes.

3) Using Logistic Regression with Grid Search Cross Validation & Liblinear Solver, the AUC value is still 58%.

4) By applying Logistic Regression with Grid Search CV & Saga Solver is also having the same AUC value, which  is 58%.

5) Upon applying Decision trees classification model, the score has improved to 80%.

6) Then again, we executed Decision tree with grid search cross validation which gave a score of 88%.

7) With the Adaboost model, we got ROC_AUC score of 52%, which is way less comparing to decision tree and logistic regression models.

8) After implementing Adaboost model, we implemented Support vector model which gave a score of 74%..

9) Lastly, we used K- Nearest Neighbors model that enhanced the ROC_AUC score around 84%.

10) On concluding, decision tree classifier has the highest score. Thus, we use this model for further deployment when implanting with live application.

**Results:**

| Model      | AUC Score |
| :---        |    :----:   |
| Logistic regression      | 58% | 
| Logistic regression with Grid seach CV and Liblinear solver    | 58% | 
| Logistic regression with Grid seach CV and Saga solver     | 58% | 
| Decision Tree   | 80% | 
|  Decision Tree using Grid search CV    | 88% | 
| Adaboost model | 52% | 
| Support vector machine     | 74% | 
| K- Nearest neighbor | 84%    |
