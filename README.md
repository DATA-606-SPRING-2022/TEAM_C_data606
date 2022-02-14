# TEAM_C_data606
#### This project is part of DATA-606 Capstone project TEAM-C

##### Title: 

End to End data science application which can be leveraged by banks to assess creditworthiness, lower bad debt burden, and increase the trust in the existing data rather than document-based assessment.

![image](https://user-images.githubusercontent.com/71124557/153785711-9a173674-c2b8-4801-a216-32cff8169ea3.png)

##### Background Information: 

Money lending has been a prominent activity to make money out of money. Institutional banking agencies & many individuals are pursuing this activity to make themselves profitable. After thorough research, we've found that with the technologies like decentralization finance and other technologies in place there must be a data-driven approach to solve the gap in the banking sector for accessing the customers better in terms of lowering the burden of bad debts and creditworthiness of the applicants.

##### Severity of the issue: 

After the global financial crisis, we've found that with the availability of better-skilled workers in many industrial sectors and better cash flows with increased income levels in individuals the roadblocks in accessing the capital are not eliminated (below graph shows the same).

![image](https://user-images.githubusercontent.com/71124557/153785722-a606e313-fa6b-4a76-b91f-b0a8c922ea4b.png)

##### Existing problems in the banking sector:

1. Lack of data-driven approach in accessing the customer.
2. Following the same traditional methodology of underwriting the collateral to grant the loans.
3. Does not consider the steady cash flow of the individuals to estimate the risk.
4. Improper accessing customers solely based on collateral.

##### Goals of the Project: 

To incorporate an end-to-end data science project which could address the existing gaps in the banking sector by powering them with a web-based dashboard to access the creditworthiness of the customer.

![image](https://user-images.githubusercontent.com/71124557/153785776-7d00f715-caef-4d58-959b-2ac52afdda15.png)
This project aims to address the gap of improper customer assessmnet and developing a new way to access the customers by the data driven approaches

##### Dataset Description:

ID: Customer ID of Applicant

year: Year of Application

loan_limit: Cash Flow or Net Cash Flow type

gender: Applicant's gender

approv_in_adv: Is loan pre-approved or not

loan_type: Type of loan

loan_purpose: Purpose of loan

Credit_Worthiness: Credit worthiness of the applicant

open_credit: Type of Credit (Open credit or Non open credit)

business_or_commercial: Usage type of the loan amount

loan_amount: The exact loan amount

rate_of_interest: Rate of interest of the loan

Interest_rate_spread: Spread of interest rate by banks

Upfront_charges: Up front loan sanctioning charges

lump_sum_payment: Down payment for the loan

property_value: Collateral value

construction_type: Collateral construction type

age: Age of applicant

Security_Type: Type of Collatoral

status: Loan status (Approved/Declined)

#### Data source- https://www.kaggle.com/yasserh/loan-default-dataset

Unit of Analysis: Loan record of applicant.

Number of observations to be analysed: 148671

Output Variable: Loan status

##### Models we are trying to use:

1. Random Forest with Grid search CV

2. Logistic Regression with Grid search CV

3. Support Vector Machine with Grid search CV

4. K Nearest Neighbors with Grid search CV

5. Bagging with Base estimator as Random Forest

6. Bagging with Base estimator as Logistic Regression

7. AdaBoost Classifier

8. Multilayer Perceptron Classifier

9. Neural Networks

10. Tensor Flow.

##### Evaluation metrics to be used: 

We are planning to evaluate the metrics such as recall, accuracy, precision, f-1 score, confusion matrix, ROC-AUC scores. After determining the metric to evaluate the model with the help of the business understanding of the domain of the data, we'll figure out the ways to improve the performance of the model.

##### Expected Outcomes:

1. Importance of business domain understanding in choosing and evaluating the model.

2. To apply various machine learning models to classify the outcome.

3. Usage of Various evaluating metrics to determine the performance of the model.

4. Importance of Various Statistical Analysis Understanding the Dimensionality Reduction.

5. Understanding the Bias-Variance trade-off.

6. Application of Principal component analysis.

7. Usage of Grid search Validations.

8. Understanding of Various activation functions.

9. Effectively handling the outliers.

10. Usage of various hyperparameters.

11. Analyzing & Visualizing the data.

12. Building a dashboard which helps banking stakeholders to access the status of creditworthiness.

### Roles & Responsibilities

Narendra Thuma:

- Implementing various classification algorithms like Logistic Classification
- Naive Bayes
- SVM
- Decision Trees
- KNN & ensembling modelling
- Developing an algorithm to access the credit risk in lending
- Dashboard development

Vaishnavi Vejella:

- Data gathering
- Data Cleaning
- Data Visualization
- Finding business value in developing the model.
- Dashboard development

Rakesh Reddy:

- Choosing the right evaluation metric to gauge the performance of the developed model
- Performing various statistical analysis on the data
- Interpretation of the results of statistical analysis
- Dashboard development
