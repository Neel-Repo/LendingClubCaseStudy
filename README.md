# Lending Club Case Study
> To identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.


## Table of Contents
* The problem Statement
* Data Understanding
* Data Cleaning & Manipulations
* Data visualization and feature engineering
* Conclusions


<!-- You can include any other section that is pertinent to your problem -->
## The problem Statement
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 
- Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. 

## Data Understanding
- important Features & Descriptions
- Data Set Raw Insights

## Data Cleaning & Manipulations
- Data Sanitization
- Manipulations
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Data visualization and feature engineering
- Univariate Analysis and distribution of features
- Bivariate Analysis & Multivariate Analysis
- Correlation Matrix

## Conclusions
Based on the correlation values the following variables have a positive correlation with the "loan_status_bit" feature:
loan_amnt: 0.076499
funded_amnt: 0.073149
funded_amnt_inv: 0.046281
term: 0.176951
installment: 0.042059
issue_d: 0.032325
verification_status: 0.031629
dti: 0.046339
balance_annual_inc: 0.127828
The positive correlation coefficient suggests that as the value of these variables increases, the likelihood of loan default also increases.
On the other hand, the following variables have a negative correlation with the "loan_status_bit" feature:
grade: -0.203700
sub_grade: -0.206201
annual_inc: -0.057067
home_ownership: -0.011517
emp_length_num: 0.027814
The negative correlation coefficient suggests that as the value of these variables decreases, the likelihood of loan default increases.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Python  - version 3.0

## Contact
Created by @Neel-Repo - feel free to contact me!
