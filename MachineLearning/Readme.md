**This folder contains python notebooks and reports explaining Machine Learning Models.**

**Link to Presentation** - https://github.com/vvejella/TEAM_C_data606/blob/main/Presentations/TEAM-C-PPT_Draft.pptx

**Link to Video Presentation:** - https://youtu.be/n0ATtXOPFwU

**Columns in the data set:**

ID: Customer ID of Applicant

year: Year of Application

loan_limit: Cash Flow or Net Cash Flow type

gender: Applicant's gender

approv_in_adv: Is the loan pre-approved or not

loan_type: Type of loan

loan_purpose: Purpose of loan

Credit_Worthiness: Creditworthiness of the applicant

open_credit: Type of Credit (Open credit or Non-open credit)

business_or_commercial: Usage type of the loan amount

loan_amount: The exact loan amount

rate_of_interest: Rate of interest of the loan

Interest_rate_spread: Spread of interest rate by banks

Upfront_charges: Upfront loan sanctioning charges

lump_sum_payment: Down payment for the loan

property_value: Collateral value

construction_type: Collateral construction type

age: Age of applicant

Security_Type: Type of Collateral

status: Loan status (Approved/Declined)

**Source of Dataset:**

https://www.kaggle.com/yasserh/loan-default-dataset

**Unit of Analysis**: Loan record of the applicant.

**Size of the data**

Number of observations to be analyzed: 148671
Number of columns: 34

**5Missing Values:** 

![missing](https://user-images.githubusercontent.com/91147579/155860766-18c68d22-bfd4-4037-ad77-cf45e0970ee9.JPG)

The columns rate_of_interest, interest_rate_spread, upfront_charges, property_value have missing values which can be seen as the gaps in the column bars.



**Machine Learning Models Used:**

1) Logistic Regression

2) Logistic Regression using Grid Search Cross Validation at various regularization strengths and liblinear solver

3) Logistic Regression using Grid Search Cross Validation at various regularization strengths and saga solver

4) Decision Tree Classifier

5) Decision Tree with Grid Search CV

6) Support Vector Machine

7) K-Nearest Neighbours

8) Adaboost Model


**Results & Conclusions:**

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

