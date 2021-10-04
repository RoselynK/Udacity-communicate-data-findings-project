# Prosper Loan Data Exploration
## by Roselyn N. Kinuthia


## Dataset

This data set contains information on peer to peer loans facilitated by credit company Prosper. There are 113,937 loans with 81 variables. However, I chose a few variables to focus on in my analysis. These were: 'Term', 'LoanStatus', 'BorrowerAPR', 'BorrowerRate', 'ProsperRating (Alpha)', 'ProsperScore', 'ListingCategory (numeric)','EmploymentStatus', 'DelinquenciesLast7Years', 'StatedMonthlyIncome' 'TotalProsperLoans', 'LoanOriginalAmount','LoanOriginationDate', 'Recommendations', 'Investors'. The dataset is available here: https://video.udacity-data.com/topher/2021/May/60908116_dataset-project-communicate-data-findings/dataset-project-communicate-data-findings.pdf and the data dictionary is available here: https://docs.google.com/spreadsheets/d/1gDyi_L4UvIrLTEC6Wri5nbaMmkGmLQBk-Yx3z0XDEtI/edit#gid=0. For data cleaning, i removed records with NAs in the prosper rating column and removed records that had a prosper score of above 10. I also changed the loan origination date to datetime.




## Summary of Findings

### Univariate Data Analysis: 

Loan Status - Majority of the loans featured are current loans
Employment Status - Majority of the borrowers are employed
Prosper score  The mode was 4 ith majority of borrowers scoring between 4 and 8
Stated monthly income - This was skewed to the left with a few outliers having high income amounts
Loan original amount - This was also skewed to the left.

### Bivariate and Multivariate analysis:
Focusing on a smaller group of borrowers who have completed their loans and defaulters, I realized that most of the defaulters have a lower prosper rating with the most common being D. Also, their prosper scores are lower and the involved original amounts for the defaulters is higher compared to those who have completed. This analysis helped in bringing out te features strongly as compared to the univariate analysis.



## Key Insights for Presentation

for my presentation, i will focus on the prosper score, prosper rating, employment status and loan original amount variables and how they affect the loan status.
