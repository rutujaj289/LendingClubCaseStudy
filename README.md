
# Lending Club Case Study

This project analyzes loan data to predict loan default, using historical data on applicants' repayment behavior (fully paid, current, charged-off). It aims to aid a consumer finance company in making informed loan approval decisions by identifying risky applicants early, potentially reducing credit losses and enhancing risk assessment.

## Table of Contents

1. [General Information](#general-information)
2. [Business Objective](#business-objective)
3. [Dataset Description](#dataset-description)
4. [Methodolody](#methodology)
5. [Conclusions](#conclusions)
6. [Technologies Used](#technologies-used)
7. [Acknowledgement](#acknowledgements)
8. [Contact](#contacts)
## General Information

This project aims to analyze loan data to identify patterns and indicators that predict loan default. The dataset contains historical data on loan applicants and their repayment behavior, categorized into various loan statuses such as fully paid, current, and charged-off (defaulted).

The goal is to help the consumer finance company make informed decisions regarding loan approvals by identifying risky applicants early in the process. This will potentially reduce credit losses and improve the overall risk assessment process.
## Business Objective

The primary objectives of this project are:

1. Identify key factors influencing loan default.
2. Develop insights to help in decision-making related to loan approvals.
3. Implement strategies to mitigate financial losses due to default.
## Dataset Description

The dataset includes the following attributes:

1. Customer attributes: Information about the applicants such as age, employment status, income, etc.
2. Loan attributes: Details about the loan amount, interest rate, term, etc.
3. Loan status: Outcome of the loan application (fully paid, current, charged-off).

## Methodology

__Exploratory Data Analysis (EDA)__

EDA will be performed to:

1. Explore the distribution of loan statuses (fully paid, charged-off, etc.).
2. Analyze the relationship between customer attributes, loan attributes, and loan status.
3. Identify correlations and patterns that indicate higher risk of default.

## Conclusions

**Major Driving factor which can be used to predict the chance of defaulting and avoiding Credit Loss:**

1. DTI
2. Grades
3. Verification Status
4. Annual Income
5. Public Record Bankruptcies


**Other Conclusions:**

1. Majority of borrowers asked for rounded number that is 5000 , 10,000, 12000.
2. Majority of the people have took the 36 months tenure period
3. Majority of the people have taken loan in the end of the year
4. Majority of the people have taken loan in 2011 and after every year, the number of loan borrowers have increased
5. California state has highest number of loan count
6. People having 10+ year experience are majority of applicants of the loan
7. Majority of the people who applied for the loan are living on rent or mortgage
8. The interest rate in charged off were higher than that of fully paid which may infer that higher interest rate could result in higher charge offs
9. The percentage of defaulters are higher in 60 months term with about 25% charge-off whereas it is just 11% for 36 month term. So, there is a possibility that longer term loans are more risky and prone to higher default
10. People having less income are more likely to default.
11. As the grades gets lower, charge off rate increases proportionately
12. As the sub-grades gets lower, charge off rate increases proportionately
13. Higher the dti,more likely the charge off
As number of bankruptcies increases the charge off rate also increases
## Technologies Used

1. Pandas 
2. NumPy 
3. MatplotLib 
4. Seaborn
## Acknowledgements

This project was created as a case study for IITB Machine Learning and AI program.

## Contact

Created by [@rutujaj289](#@rutujaj289) - feel free to contact me!