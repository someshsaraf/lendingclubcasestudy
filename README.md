# Lending Club Case Study

####  Team :
- Somesh Saraf
- Saudip Sen

## Table of Contents
* [Problem statement](#general-information)
* [Analysis approach](#general-information)
* [Technologies Used](#technologies-used)


## Problem statement
- Like most other lending companies, lending loans to ‘risky’
applicants is the largest source of financial loss (called credit
loss). Credit loss is the amount of money lost by the lender
when the borrower refuses to pay or runs away with the money
owed. In other words, borrowers who default cause the largest
amount of loss to the lenders. In this case, the customers
labelled as 'charged-off' are the 'defaulters'.

- If one is able to identify these risky loan applicants, then such
loans can be reduced thereby cutting down the amount of credit
loss.

- Identification of such applicants is the objective of the project.

## Analysis approach used
- Data Understanding
- Data clean up
- Univariate analysis
- Bivariate analysis
- Trivariate analysis

Conclusion:
The analysis shows lot of individual parameters affect the applicants to become defaulters.
Below is the conclusion:
- Interest rate between 14% and 17% tend to be defaulters.
- Loan amounts between 5K and 10K show the trend for defaulters.
- Loan tenures of 36 months tend to default more.
- People on RENT are risky for defaulters
- Verification status as "Not Verified" have some chance to default.
- Grade B loans are probable to default
- Sub grades A3,A5,D5,A2 tend to be defaulters.
- DTI in range of 10 and 20 is little risky

The analysis also shows how parameters in combination affect the applicants to become defaulters.
Below is the conclusion:
- 'Not Verified' with house ownership as RENTED is not good.
- Loan Amount between 5k-10k taken when house ownership is RENT is a risky loan.
- House ownership as RENT taking loan with interest rate between 10-15% can cause default loans.
- People taking 36 months loan for debt_consolidation are defaulters.
- Loans of 5-10k amount and interest rate between 10-15% can cause default loans.

## Technologies Used
- Python (3.8.5)
- numpy (1.19.2)
- Pandas library (1.1.3)
- Mathplotlib library (3.3.2)
- Seaborn library (0.11.0)


