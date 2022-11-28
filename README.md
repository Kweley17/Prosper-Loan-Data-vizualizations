## Dataset
The dataset investigated was the `Loan Data from Prosper`. It is a relatively large datsaet with alot of variables. It contains loans data from the year 2005 up until 2014. 
For my approach only a few of the aforementioned variables will be explored.

## Summary of findings
During my study, I came up with the following conclusions
There seems to be very little of 2005 data provided on the dataset closely followed by 2009 which has more data but ultimately quite little. 
Most of the loan amounts borrowed fall within the 4000 dollar mark. 
From the dataset, we can see that the majority of the loans are still `current` meaning that they are yet to be fully repaid but are still within the next payment window. 
The `BorrowerRate` and `BorrowerAPR` are very closely related as they represent somewhat similar ideas. Most of the values appear to attract a `Borrowerrate` and `BorrowerAPR` of 0.3 and 0.3-4 respectively.

>Homeowners are seen to be the more frequent loaners compared to non homeowners. 
Employed folk also appear to be more likely to take up loans compared to non-employed folk. 
Ther year 2013 recorded the highest amounts of loans borrowed, with 2005 recording a nearly misleading least, pointing to the possibility of missing data. 
From the provided data, it does not seem like plenty of the loans received investment from friends. 
`Investors` distribution could be considered normal save for the fact that there is a large amount of loans (the majority) having 1 investor.

## Key Insights of Presentation
From the visualization of the histogram showing distribution of `StatedMonthlyIncome`, we can see that it takes a normal distribution. The plot is unimodal with a peak at around 4000 dollars
For the next visualization, `LoanOriginalAmount` is plotted against `EmploymentStatus`, grouped by `Homeowner status`. This plot conveys to us that most loaners are homeowners. Most of the loaners are also employed
The final plot contains two subplots of `BorrowerRate` and `BorrowerAPR` both against `LoanOriginalAmount`. From the plots we can deduce how closely related these two variables are, with nearly identical plots against the same variable. A ton of the values fall in between 0.3-0.4 rates and just under 15000 Loan amount


