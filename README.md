TEAM_C_data606
This project is part of DATA-606 Capstone project -TEAM-C
Title: End to End data science application which can be leveraged by banks to assess creditworthiness, lower bad debt burden, and increase the trust in the existing data rather than document-based assessment.

1_ZQ25X7Qnq6ui83yc8RB5pQ

Background Information: Money lending has been a prominent activity to make money out of money. Institutional banking agencies & many individuals are pursuing this activity to make themselves profitable. After thorough research, we've found that with the technologies like decentralization finance and other technologies in place there must be a data-driven approach to solve the gap in the banking sector for accessing the customers better in terms of lowering the burden of bad debts and creditworthiness of the applicants.

Severity of the issue: After the global financial crisis, we've found that with the availability of better-skilled workers in many industrial sectors and better cash flows with increased income levels in individuals the roadblocks in accessing the capital are not eliminated (below graph shows the same).

ecb ebart202004_02 en_img0

Existing problems in the banking sector:

Lack of data-driven approach in accessing the customer.
Following the same traditional methodology of underwriting the collateral to grant the loans.
Does not consider the steady cash flow of the individuals to estimate the risk.
Improper accessing customers solely based on collateral.
Goals of the Project: To incorporate an end-to-end data science project which could address the existing gaps in the banking sector by powering them with a web-based dashboard to access the creditworthiness of the customer.

determining-customer-creditworthiness thumb 1280 1280

This project aims to address the gap of improper customer assessmnet and developing a new way to access the customers by the data driven approaches

Dataset Description:

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

Data source- https://www.kaggle.com/yasserh/loan-default-dataset

Unit of Analysis: Loan record of applicant.

Number of observations to be analysed: 148671

Output Variable: Loan status

Models to be used:

Random Forest with Grid search CV

Logistic Regression with Grid search CV

Support Vector Machine with Grid search CV

K Nearest Neighbors with Grid search CV

Bagging with Base estimator as Random Forest

Bagging with Base estimator as Logistic Regression

AdaBoost Classifier

Multilayer Perceptron Classifier

Neural Networks

Tensor Flow.

Evaluation metrics to be used: we are planning to evaluate the metrics such as recall, accuracy, precision, f-1 score, confusion matrix, ROC-AUC scores. After determining the metric to evaluate the model with the help of the business understanding of the domain of the data, we'll figure out the ways to improve the performance of the model.

Expected Outcomes:

Importance of business domain understanding in choosing and evaluating the model.

To apply various machine learning models to classify the outcome.

Usage of Various evaluating metrics to determine the performance of the model.

Importance of Various Statistical Analysis Understanding the Dimensionality Reduction.

Understanding the Bias-Variance trade-off.

Application of Principal component analysis.

Usage of Grid search Validations.

Understanding of Various activation functions.

Effectively handling the outliers.

Usage of various hyperparameters.

Analyzing & Visualizing the data.

Building a dashboard which helps banking stakeholders to access the status of creditworthiness.

Roles & Responsibilities

Narendra Thuma:

Implementing various classification algorithms like Logistic Classification
Naive Bayes
SVM
Decision Trees
KNN & ensembling modelling
Developing an algorithm to access the credit risk in lending
Dashboard development
Vaishnavi Vejella:

Data gathering
Data Cleaning
Data Visualization
Finding business value in developing the model.
Dashboard development
Rakesh Reddy:

Choosing the right evaluation metric to gauge the performance of the developed model
Performing various statistical analysis on the data
Interpretation of the results of statistical analysis
Dashboard development
