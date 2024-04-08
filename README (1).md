# Project Name
> Lending Club Problem


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)


## General Information
The data given had information about past loan applicants and whether they 'defaulted' or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

hen a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

Business Objective: The company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 


## Conclusions
After analysing all the multivariate charts, we can clearly observe the potentially strong indicators/predictors of loan default.

These are following-

annual_inc - The self-reported annual income provided by the borrower during registration.
grade/sub-grade - LC assigned loan grade
last_pymnt_amnt - Last total payment amount received
term - The number of monthly payments on the loan.
int_rate - Interest Rate on the loan
dti - A ratio calculated using the borrower's total monthly debt divided by the borrower's self-reported monthly income.
revol_util - Amount of credit the borrower is using relative to all available revolving credit.


Out of these 7 indicators **annual_inc, grade and last_pymnt_amnt** are most potential indicators for identifying loan defaults.
Reason for their selection- There are few more variables which have shown strong trends with loan default status, however those variables are not as good indicators as above mentioned variables because these selected variables individually and in combination with each other, seperate the loans with higher default rate and not nullifying their combining impact on loan default rate.

These variables, in together, have increased the degree of separability between loan default or not-default, thus are potential indicators. Therefore, achieving the objective of problem statement of Lending Club Case Study.


## Contact
Created by [@arunimahait] - feel free to contact me!

