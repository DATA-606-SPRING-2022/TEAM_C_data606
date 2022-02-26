**This folder conatins python notebooks and report explaining Exploratory Data Analysis (EDA).**

**1) The columns in the data set are: **

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

**2) Source of Dataset:**

https://www.kaggle.com/yasserh/loan-default-dataset

**3) Unit of Analysis**: Loan record of applicant.

**4) Size of the data**

Number of observations to be analysed: 148671
Number of columns: 34

**5) Missing Values:** 

![missing](https://user-images.githubusercontent.com/91147579/155860766-18c68d22-bfd4-4037-ad77-cf45e0970ee9.JPG)

The columns rate_of_interest, interest_rate_spread, upfront_charges, property_value has missing values which can be seen as the gaps in the column bars.

**6) Analysis on distribution of loan amounts:**

![image](https://user-images.githubusercontent.com/91147579/155860799-3c763e97-ba81-4f27-bd05-56abf1bfede1.png)

Most of the values of loan applications are in the ranges beween 250 K to 500 K

**7) Analysis on Distribition of loan applications by gender:**

![image](https://user-images.githubusercontent.com/91147579/155860817-5f9cc9be-c4c3-41d4-8d6e-e62f34a44118.png)

We can infer that the joint applications (i. e., both male and female) are the highest and individually male application sare higher than females.

**8) Analysis on Distribution of loan applicants by credit type:**

![image](https://user-images.githubusercontent.com/91147579/155860843-bec09bc0-d0c3-4016-88d0-0b1df24833e9.png)

The loan applications with 'CIB' & 'CRIF' are the highest when comapred to other two types.

**9) Analysis on Distribution of loan applicants by occupancy type:**

![image](https://user-images.githubusercontent.com/91147579/155860881-864d5d7a-5ecc-4f3a-baa8-a8b5ffbca1e6.png)

The loan applications with occupany_type 'pr' are the highest when compared to the other types of accupancies.

**10) Analysis on Distribution of loan applicants by purpose of the loan:**

![image](https://user-images.githubusercontent.com/91147579/155860904-074a4e81-5b92-4778-8cf8-4750ca0936d9.png)

The purposes 'p3','p4' types are the highest among other loan applications.
