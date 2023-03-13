# Exploring The Prosper Loan Data
## by Godswill Sedem Buabassah


## Dataset

> Prosper Loans is the first peer-to-peer lending marketplace in the US that has facilitated over 23 billion USD in loans to more than 1.4 million borrowers since its founding in 2005. It offers borrowers fixed-rate, fixed-term loans between USD 2,000 and USD 50,000, while investors can invest in the loans and earn attractive returns. 

>The data set contains 113,937 loans with 81 variables. There are both numerical and categorical data with numerical data being majority. The variables of the dataset provides a rich source of information detailing the circumstances of each loan. However after thorough cleaning there are 84853 records with 70 variables and this analysis only focuses on 23 variables.

>The dataset can be found here https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv, with feature documentation available here https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0

>The exploration is to gain insights into the various factors that influence borrower behavior when applying for loans, with a focus on identifying the determinants for aquiring loans. To accomplish this goal, we will concentrate our exploratory efforts on Prosper Rating and Original Loan Amount.

## Summary of Findings

> Based on the findings of the study, it can be inferred that the majority of individuals who obtained loans from Prosper used the money to consolidate their debts, and the 36-month payment period was the preferred option. Full-time employment and verified monthly salary were common among borrowers.

>The study also revealed a strong negative correlation between Prosper rating and borrower rate, borrower APR, and lender yield. Loan amount had a moderate negative correlation with Prosper rating, lender yield, and borrower rate and APR.

>Although there were no statistical tests conducted to support the claim, borrower income range was observed as an essential factor that influenced Prosper rating. Interestingly, whether a borrower owned a home or not, did not affect the Prosper rating. However, home ownership played a significant role in determining the loan amount.

>In conclusion, borrowers with lower Prosper ratings were more likely to borrow smaller amounts with higher interest rates. On the other hand, borrowers with higher Prosper ratings were more likely to obtain larger loans with lower interest rates. Loan term and rating also interacted, with loan amounts increasing as the Prosper rating improved, especially between different terms.


## Key Insights for Presentation

>Based on the findings of the study, it can be inferred that the majority of individuals who obtained loans from Prosper used the money to consolidate their debts. 

>The study also revealed a strong negative correlation between Prosper rating and borrower rate, borrower APR, and lender yield. Loan amount had a moderate negative correlation with Prosper rating, lender yield, and borrower rate and APR.

>Although there were no statistical tests conducted to support the claim, borrower income range was observed as an essential factor that influenced Prosper rating. The higher the income range, the better the Prosper rating. The loan amount is influenced by the Income Range of the borrower, with higher incomes being more likely to result in larger loans.

>Borrowers with lower Prosper ratings are more likely to borrow smaller amounts with higher interest rates. On the other hand, borrowers with higher Prosper ratings are more likely to obtain larger loans with lower interest rates. 

> To ensure effective communication of findings, explanatory labels, ticks titles were added to the visuals.