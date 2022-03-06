# Lending Club
A consumer finance company which specialises in lending various types of loans wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

A consumer finance company which specialises in lending various types of loans to urban customers, receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile.Two types of risks are associated with the bank’s decision:

  - If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
  - If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc

When a person applies for a loan, there are two types of decisions that could be taken by the company:
  - Loan accepted: If the company approves the loan, there are 3 possible scenarios described below: 
    - Fully paid
    - Current: Applicant is in the process of paying the instalments
    - Charged-off: Applicant has not paid the instalments in due time for a long period of time
  - Loan rejected

#### What we need to identify ?(Approach)


- Does a borrower defaults if funded amount is greater than the average funding amount

- Does a borrower defaults if interest rates are higher than average interest rate

- Do borrowers defaults who have high installments.

- Do emp_length of a borrower affect borrower to default?

- Do type of home ownership have any affect on borrower to default.

- Do high dti determines if a borrower will default or not ?

## Conclusions


Lending club can reduce the charged off customers by considering below points:

- Reducing the high interest rates.

- Capping the loan amount or stopping the loan approvals for small business purpose.

- Proper review of information from borrowers before approving grade G and F loans and particularly  for G3, F5 and G2 sub grade loans.

- Reducing the number of approved loans for borrowers who are from states CA, FL and NY. Or capping the loan amount

- Capping the loan amount for borrowers whose annual income is low and debt is high.





## Technologies Used
- Pandas 1.3.4
- Seaborn 0.11.2
- Matplotlib
- Spacy 3.2.2


## Contact
Created by [@himanshubirla] - feel free to contact me! E-Mail : himanshubirla@outlook.in or himanshubirla.91@gmail.com


