# Prosper Loan Data Exploration
## by Menzi Khumalo


## Dataset

> The dataset investigated consisted of borrower APRs and attributes of 113,937 loans. The attributes included original loan amount, borrower's Prosper rating, loan term, borrower's stated monthly income, as well as many other features such as borrower's employment status, debt to income ratio, current loan status e.t.c


## Summary of Findings

>In the exploration, I found that the borrower APR is negatively correlated with original loan amount. At different size of the loan amount, the APR has a large range, but the range of APR decrease with the increase of loan amount. The borrower APR also decreases with the increasingly better rating. Borrowers with the best Prosper ratings have the lowest APR. It means that the Prosper rating has a strong effect on borrower APR. Interestingly, the relationship between borrower APR and loan amount turns from negative to slightly positive when the Prosper score increases. People with low Prosper scores tend to borrow less money, decreasing APR could encourage them to borrow more. .


## Key Insights for Presentation

>For the presentation, I just focus on features that could affect the borrower APR, which are original loan amount, Prosper rating and income range. I started by showing the distribution of borrower APR. Then, I showed the relationship between APR vs. loan amount, as well as APR vs. Prosper rating. I also investigated the effect of rating on relationship between APR and loan amount, as well as the effect of loan amount on relationship between borrower APR and income range.

## Tools
* _Numpy_
* _Pandas_
* _Seaborn_
* _MatplotLib_
