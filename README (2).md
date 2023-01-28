# Prosper Loan Dataset Exploration 
## by Robyn Hoover


## Dataset

> > The Prosper Loan data contains 113,937 loans with 81 variables on each loan, including loan amount, interest rate, APR, loan type, current loan status, borrower income, and many others. 

> This data dictionary was used to interpret all 81 variables: https://www.google.com/urlq=https://docs.google.com/spreadsheet/ccckey%3D0AllIqIyvWZdadDd5NTlqZ1pBMHlsUjdrOTZHaVBuSlE%26usp%3Dsharing&sa=D&ust=1554486256024000. 

> The data set can be found here: https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000. 

## Summary of Findings

### Univariate Findings

> Most of the interest rates fell between 10-25%.
> Debt consolidation loanss are the most popular.
> The most common credit scores fell between 660-750
> Most of the loans were less than 15,000 dollars
> No conclusions can be drawn from the state data currently.
> The most common income range was 25,000-49,000 dollars.
> The most common loan term was 36 months.
> Most of the interest rates fell between 10-25%.

### Bivariate Findings
> The heat map comparing interest rates to the amount borrowed shows the strongest correlation where loans less than $5000 have an interest rate between 25-30%.
> There is a strong linear correlation between the interest rate an the annual percentage rate (APR).
> The highest APR and interest rate average are both for category 10, loans for cosemetic procedures.
> A loan term of 12 months or less has lower interest rates than the loan terms of 36 or 60 months. There is not much of a differnce in interest rate between loan terms of 36 and 60 months.
> A higher income appears to be correlated with a lower interest rate.
> A higher credit score range seems to be correlated with a lower interest rate.

### Multivariate Findings
> Borrowers with lower income ranges and unemployed borrowers tend to have higher interest rates. Interest rates do not seem to differ much by state.
> A higher income and higher credit score tends to lead to a lower interest rate, but having a higher credit score is more important than having a higher income though when trying to obtain a lower interest rate.
> A higher credit score and a loan term of 12 months tend to have the lowest interest rates. Credit score seems to still be the most important factor though.
> Certain loan types have higher interest rates than others, but having a higher credit score can help reduce the interest rate.

## Key Insights for Presentation

> A higher credit score range seems to be correlated with a lower interest rate.
> Suprisingly, a smaller loan amount can lead to a higher interest rate.
> The loan term, loan amount, loan type, and borrower income range are also important factors to determine interest rates.
> The majority of the loans in this dataset were less than $15,000.