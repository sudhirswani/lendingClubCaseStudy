# Lending Club Case Study
> The case study focuses on EDA, to understand key drivers for loan default based on the data provided.
Included pdf file presents data distributions across each driving parameter, key observations and comparisons across loan status categories.


## Table of Contents
* [General Info](#general-information)
* [Thought process](#thought-process)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
### Case Study Brief:
You work for a consumer finance company which specializes in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant's profile. Two types of risks are associated with the bank's decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

When a person applies for a loan, there are two types of decisions that could be taken by the company:
1. Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
	- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
	- Current: Applicant is in the process of paying the installments, i.e. the tenure of the loan is not yet completed. These candidates are not labeled as 'defaulted’.
	- Charged-off: Applicant has not paid the installments in due time for a long period of time, i.e. he/she has defaulted on the loan
2. Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

### Business Objectives:
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labeled as 'charged-off' are the 'defaulters'.

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilize this knowledge for its portfolio and risk assessment.

## Thought process
- We tried to find out how many loans tend to get charged off.
- We checked distributions of loan amount, interest rates, annual income for all loans.
- We checked loan status proportions for each category across various purposes, home ownership categories, loan terms, grades, subgrades, employment lengths and address states 
- We tried to find out trends of charged off loans for various range of annual income, loan amounts, interest rates, revolving line utilization rates, dti, bankruptcy records and year of issue.


## Conclusions
With analysis we found key driving parameters for defaulting loans as follows,
- High Interest Rates: The highest default rates correlate strongly with higher interest rates.
- High Revolving Line Utilization Rates: Increased utilization rates on revolving lines are linked to higher default percentages.
- Lower Loan Grades: Loans with lower grades (e.g., G and F) have significantly higher default rates.
- Public Bankruptcy Records: More public bankruptcy records indicate a higher risk of loan default.
- Higher Loan Amounts: Larger loan amounts generally have a higher default risk.
- Loan Purpose: Specific purposes, such as small business loans, show higher default rates.
- Loan Term: Longer loan terms, like 60 months, have a higher likelihood of default compared to shorter terms.
- Annual Income: Lower annual income levels are associated with higher default rates.


## Acknowledgements
We sincerly thank to Upgrad team, IITB Professors and SMEs who guided us timely to complete this assignment.


## Contact
Created by [Sudhir Wani](https://github.com/sudhirswani)

