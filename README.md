# Dataset from Prosper on Loan
A Dataset from Prosper oraginization. 

## Summary of the Dataset 
The dataset is about loan giving to customers of the Prosper organization, the dataset contain 81 distinct variables(columns) and 113937 rows of data or information pertaining to a particular loan giving to a new or old borrower of the orgainzation, the dataset contain details like the total amount borrowed, the length of the loan, the status of the loan like cancelled, charged off, completed, past due etc.

### Explanation of some of the term 

1. Loan Original Amount: The origination amount of the loan.

2. Prosper Principal Borrowed: Total principal borrowed on Prosper loans at the time the listing was created. This value will be null if the borrower had no prior loans.

3. Prosper Rating (Numeric) : The  Prosper Rating assigned at the time the listing was created: 0 - N/A, 1 - HR, 2 - E, 3 - D, 4 - C, 5 - B, 6 - A, 7 - AA.  Applicable for loans originated after July 2009.

4. Amount Delinquent : Dollars delinquent at the time the credit profile was pulled. (more definition from Google)-- The term delinquent refers to the state of being in arrears. When someone is delinquent, they are past due on their financial obligation(s), such as a loan, credit card, or bond payments. This means a borrower's payments are not made to satisfy their debt(s) in a timely manner

5. Income Range: The income range of the borrower at the time the listing was created.

6. Lender Yield: The Lender yield on the loan. Lender yield is equal to the interest rate on the loan less the servicing fee.

### Insight to Explore
1. The relationship between the Loan Original Amount, Prosper Principal Borrowed, Prosper Rating (Numeric)

2. The correlation between prosper score and lender yield where stated monthly income is not zero(0) and is more than $10

3. The relationship between interest rate of people whose, monthly due for the all month in the dataset is not zero

### Tools and Libraries Used:
 - Anaconda
 - Jupyter Notebook
 - Pandas
 - Matplotlib.pyplot
 - Numpy
 - Seaborn
 
 ### Conclusion
 
 For the first insight
 Looking at graph, low prosper principal borowed and loan original amount caused a low prosper rating, one can say that the graph is postively correlated, an increase in both prosper principal borrowed and loan original amount causes an increase in propser rating.
 
 For the second insight
 Using both the data on the scatter plot and the heat map, one can see that the distribution is negatively correlated, meaning customers with high prosper rating tends to have low interest rate on loan taking from the orgaanization while customers with low rating tends to have high interest rating on loan taking from the organization.
 
 For the third visualization in the slide 
 I used both the violin plot and box plot to depict the data for this insight, from the violin plot, oe can see that customers that have zero(0) income range and not employed are giving high interest rate, from the box plot the first and third quartile for customers not employed have the highest value also the median
