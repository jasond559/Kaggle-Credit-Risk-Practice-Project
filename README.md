## Python practice project
This is a practice project using Python to analyze a dataset about credit risk that was found on Kaggle. The project consisted of using Pandas and Matplotlib to determine if there are any factors in the historical loan data that would indicate a loan is more likely to default.

Once the dataset was loaded and reviewed, it was split into two subsets for loans that defaulted and loans that did not default.

The subsets were then analyzed against the total loans given to determine if any of the fields had a larger impact on the possibility of default.

Purpose of the loan, job type, and credit history were the fields chosen for closer analysis. However, it should be noted that there are other fields such as age, account balances and loan amount that could contribute to the default rate.

Based on this short analysis, it appears the purpose and job type are not strong indicators of the default rate of a loan. 
The analysis of credit history, however, provided surprising results. Based on this dataset, the most loans were given to borrowers with good or critical credit, while a much lower amount of loans were given to borrowers with perfect, very good, or poor credit. 
The rate at which borrowers with perfect or very good credit defaulted on their loans was much higher than even those with critical credit. 
