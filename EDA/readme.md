**This folder contains python notebooks and reports explaining Exploratory Data Analysis (EDA).**

**Link to Presentation** - https://github.com/vvejella/TEAM_C_data606/tree/main/Presentations 

**1) The columns in the data set are:**

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

**2) Source of Dataset:**

https://www.kaggle.com/yasserh/loan-default-dataset

**3) Unit of Analysis**: Loan record of the applicant.

**4) Size of the data**

Number of observations to be analyzed: 148671
Number of columns: 34

**5) Missing Values:** 

![missing](https://user-images.githubusercontent.com/91147579/155860766-18c68d22-bfd4-4037-ad77-cf45e0970ee9.JPG)

The columns rate_of_interest, interest_rate_spread, upfront_charges, property_value have missing values which can be seen as the gaps in the column bars.

**6) Analysis of the distribution of loan amounts:**

![image](https://user-images.githubusercontent.com/91147579/155860799-3c763e97-ba81-4f27-bd05-56abf1bfede1.png)

Most of the values of loan applications are in the ranges between 250 K to 500 K

**7) Analysis on Distribution of loan applications by gender:**

![image](https://user-images.githubusercontent.com/91147579/155860817-5f9cc9be-c4c3-41d4-8d6e-e62f34a44118.png)

We can infer that the joint applications (i. e., both male and female) are the highest, and individually male applications sare higher than females.

**8) Analysis on Distribution of loan applicants by credit type:**

![image](https://user-images.githubusercontent.com/91147579/155860843-bec09bc0-d0c3-4016-88d0-0b1df24833e9.png)

The loan applications with 'CIB' & 'CRIF' are the highest when compared to the other two types.

**9) Analysis on Distribution of loan applicants by occupancy type:**

![image](https://user-images.githubusercontent.com/91147579/155860881-864d5d7a-5ecc-4f3a-baa8-a8b5ffbca1e6.png)

The loan applications with occupany_type 'pr' are the highest when compared to the other types of occupancies.

**10) Analysis of Distribution of loan applicants by the purpose of the loan:**

![image](https://user-images.githubusercontent.com/91147579/155860904-074a4e81-5b92-4778-8cf8-4750ca0936d9.png)

The purposes 'p3', 'p4' types are the highest among other loan applications.

**11) Analysis of the distribution of Interest rates:**

![image](https://user-images.githubusercontent.com/91147579/155860930-5a167ac0-89eb-4fa8-91ba-9f882c3701e7.png)

The interest rates for most of the loans are in the range between 3 and 5.

**12) Analysis on Distribution of Loan terms (in months):**

![image](https://user-images.githubusercontent.com/91147579/155860959-42ac0afe-9d5a-4391-8e0f-ee367391bac3.png)

Most of the loan terms are in the range of 300 to 400

**13) Analysis on Distribution of Property Values:**

![image](https://user-images.githubusercontent.com/91147579/155861045-2c39ffcc-4258-4d3e-b9eb-d0e88337a8b0.png)

The values of the collateral properties for loan applications are in the ranges of 100k to 1000K

**14) Distribution of Income levels of loan applicants:**

![image](https://user-images.githubusercontent.com/91147579/155861055-7aef775a-bbd9-450d-a5fc-7274b8254190.png)

The income ranges of loan applicants are in the range of 0 to 20000 per months

**15) Analysis of age groups of loan applicants:**

![image](https://user-images.githubusercontent.com/91147579/155895467-41493153-6893-4d66-9de7-fd6760ed3b00.png)

The age of the loan applicants is in the range of 45-54 followed by applicants are of the ages 35-44.

**16) Analysis of loan amounts by interest rates:**

![image](https://user-images.githubusercontent.com/91147579/155895483-34d77114-776d-4474-8cbe-940232f29982.png)

There are no steady interest rates. We can see that the interest rates float to the loan amounts.

**17) Interest rates by Gender:**

![image](https://user-images.githubusercontent.com/91147579/155895505-8f3c14f1-b0cd-410f-8a80-70049ab3e8e4.png)

We can infer that the interest rates for loan applications do not vary by gender.

**18) Analysis of loan amounts by Gender:**

![image](https://user-images.githubusercontent.com/91147579/155895526-45a2451f-1145-4cde-8fca-e2021bafb989.png)

We can infer that the loan amount for joint loan applications is higher than followed of male applicants.

**19) Analysis of credit score by credit type:**

![image](https://user-images.githubusercontent.com/91147579/155895562-7d73940e-0540-44e6-a9fc-693164ebdc70.png)

The credit scores of the credit type CRIF are higher than those followed by credit type EXP.

**20) Analysis on loan amount by the gender of applicants type and nature of loan availability:**

![image](https://user-images.githubusercontent.com/91147579/155895588-dffb0a3a-ab52-4b3c-a8c7-588d9dcda7a0.png)

We can infer that most of the loan applicants are for commercial purposes in any ganders. We can also infer that there are male applicants for business purposes than females.
