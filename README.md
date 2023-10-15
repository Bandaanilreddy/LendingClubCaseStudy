# Lending Club Case Study

## Goals of data analysis:  

``` 
Loans to “critical” applicants are the largest source of financial loss, known as credit loss. Loan losses are the money the lender loses if the borrower defaults or defaults on the loan. 

The main purpose is to identify these risky loan applicants.
The loan amount will be reduced by reducing this loan amount. 
The purpose of this study is to identify applicants who use EDA. 

Analysis to understand the conditions (or factors) behind illegal lending
eg variable that is a strong indicator. 
Companies can use this information for verification and risk assessment.

```
## Project Information
### 1. Business Problem Statement
When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is **likely to repay the loan**, then not approving the loan results in a **loss of business** to the company

If the applicant is **not likely to repay the loan**, i.e. he/she is likely to **default**, then approving the loan may lead to a **financial loss** for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. 

We will use EDA to understand how **consumer attributes** and **loan attributes** influence the tendency of default.

### 2. Dataset
When a person applies for a loan, there are **two types** of decisions that could be taken by the company:

**Loan accepted:** If the company approves the loan, there are 3 possible scenarios described below:

- **Fully paid:** Applicant has fully paid the loan (the principal and the interest rate)

 - **Current:** Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

 - **Charged-off:** Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has **defaulted** on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

The Dataset contains the information about past loan applicants (around 113 columns & 39,000 rows) and whether they ‘defaulted’ or not. 

#### Step 1: Data Cleaning 
#### Step 2: Univariate Analysis
#### Step 3: Segemented Univariate Analysis
#### Step 4: Bivaraiate/Multivariate Analysis
#### Step 5: Results   


### Contributors
- Banda Anil Reddy




##### Developed as part of the Exloratory Data Analysis Module required for Post Graduate Diploma in Machine Learning and AI - IIIT,Bangalore.
