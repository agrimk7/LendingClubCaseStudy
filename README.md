# Lending Club Case Study
<p> Lending Club is a consumer finance marketplace for personal loans that matches borrowers who are seeking a loan with investors looking to lend money and make a return.
<br>The core objective of the excercise / case study is to help the company minimise the credit loss. There are two potential sources of credit loss are:
Applicant likely to repay the loan, such an applicant will bring in profit to the company with interest rates. Rejecting such applicants will result in loss of business.
Applicant not likely to repay the loan, i.e. and will potentially default, then approving the loan may lead to a financial loss for the company<p>


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Approach Outline](#approach-outline)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- In this case study, we use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
- the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 
- We will only be looking at all loans issued through the time period **2007 to 2011**.
- Customers whose loan staus is **'Current'** is excluded from the analysis, the loan is currently in progress and cannot contribute to conclusive evidence if the customer will default of pay in future.

## Approach Outline
- loading and exploring data
- defining the scope of analysis and variables.
- treating missing values
- analysing and treating outliers.
- Deriving additional features by transformations , grouping and bucketing.
- Performing Univariate, bivariate and correlation analyses to discover insights. 


## Conclusions
- Majority of the loan_amount is in the range of 5K to 14K
- The highest volume of loans is from CA and purely based on volumes the highest Charge Off's are from CA.
- Annual income range of 0-40K has the highest charge offs, the risk significantly decreases as income increases.
- People with known public recorded bankruptcies have a higher risk of default.
- The home ownership status of **MORTGAGE** and **RENT** are at the highest risk of Charge Offs ,and morgage based loans also tend to have a higher ticket size , increasing risk.
- A higher DTI ratio, indicating a larger portion of the borrower's income is committed to debt payments, might signal an increased risk of default.
- Very High-interest rate of **15% and above** and have higher risk of charge offs.


## Technologies Used
- `pandas` - 1.5.3
- `seaborn` - 0.12.2
- `numpy` - 1.23.5
- `matplotlib` - 3.7.1
- `jupyter notebook` - 6.4.8

## Acknowledgements
Upgrad's Data Science Ciriculum was very insightful.
- Read [here](https://www.heap.io/customer-stories/lending-club) for how lending club uses these insights.
- This project was based on the approach shared in [this tutorial](https://www.analyticsvidhya.com/blog/2021/08/how-to-perform-exploratory-data-analysis-a-guide-for-beginners/).


## Team
- Agrim [@agrimk7]
- Ajith [@ajith-shenoy]
