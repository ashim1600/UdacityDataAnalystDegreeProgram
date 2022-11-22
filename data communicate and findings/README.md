# Prosper Loan Data Exploration
## by Ashim Sharma


## Prosper Loan Dataset Insights:

> There are 113,937 loans in this data collection, and there are 81 variables. 113,937 rows and 81 columns. What characteristics are crucial for forecasting the LoanStatus in the dataset most interests me. What characteristics are particularly significant in determining whether a loan will be finished, charged off, or defaulted. Borrower Monthly Payment, Borrower Occupation, Borrower State, Borrower Employment Status, Borrower Rate, Borrower APR, Prosper Score, and Loan Amount, in my opinion, are the aspects that will aid me.

The dataset was only filtered for loan status values of Completed, Defaulted, or charged Off, as well as for ranges of credit scores more than or equal to 400.


## Summary of Findings

> Bivariate Exploration Summary
The loan status has the strongest correlation with the following attributes of all those under investigation: Recommendations and investments from friends count: Most loans below this count defaulted, but at least ten recommendations and investments from friends led to a completed loan status.Average credit score: Those who successfully repaid their loans often have scores between 650 and 750, while those who defaulted or were charged off typically have scores below 700.
Employment Status: Individuals with full-time jobs typically have greater loan completion rates than unemployed individuals.
Personal loans perform better than corporate loans, according to the listing category.
Loans with principal payments made before charged off amounts less than 1000 are not likely to be repaid in whole. While the likelihood of completion is higher for those between 2000 and 5000.
And the least discernible connection to the ensuing characteristics:
Verifiable income source: Given that both groups are more likely to default than neither group, there doesn't seem to be much of a difference in the completion rates between the two groups.
Current Group Membership: There isn't much of a difference between those in groups and those who aren't. Because of how the story is written, people who are a part of a group default equally as frequently as people who are not.
Is Borrower a Homeowner? Both homeowners and renters are more likely to default than other borrowers. ### Did you observe any interesting relationships between the other features (not the main feature(s) of interest)?
The likelihood of a friend's investment increases with the number of recommendations. This makes sense because friends are more likely to receive recommendations and loans than strangers.Prior principal payments have some relationship with the typical credit score as well.
Most people who have jobs also have dependable sources of income.


## Key Insights for Presentation

> There were many inferred links in this interesting, difficult, and perplexing dataset, which lacked any explicitly or clearly observable properties for my key variable of interest.
During this investigation stage, I anticipated two features. The most likely predictors of my variable of interest are Employment Status and Verifiable Income Sources, but I had to eliminate the Verifiable Income Source after observing its distribution relative to my variable of interest.I was able to conclude from my research that those who meet the following criteria had a higher likelihood of repaying their loans.Whether employed full-time, part-time, or otherwise is the Employement statusLoan was borrowed for private purposes.
A typical credit score of 650 to 750.More than 10 recommendations