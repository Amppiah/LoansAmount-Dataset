# Prosper Loans Data Exploration
## by Millicent Abban


## Dataset
This is a dataset consisting of about 113,937 data entries of Loans given to borrowers 
ranging from 500usd to 35,000 usd. They includes features such as employment status,
monthly income,homeownership, prosper ratings among others. 
The main purpose of the project was to find insight which can be used. It can help a 
potention investor of a finance institution who wants to understand the factors surrounding 
issuing a loan. In the analysis of the project I used pandas, matplotlib and seaborn for my 
plots.
The data set and the explanation of the variables can be found,
[Here](https://github.com/Amppiah/LoansAmount-Dataset)




## Summary of Findings
In the exploration I found that was a negative relations between Borrowrate and
Loan amounts that were given and a positive one with other variables like 
Homeowner and ProsperRates serving as influencing factors too .

*The Borrowerrate and loan amount's relationship is rather negative with rates 
largely dispersed between 0.1 and 0.3. I found that borrowers with High ProsperRatings 
are positively influence on the BorrowerRate and as well as Borrowers who own Homes. 
*The Borrowerrate and the prosper rating also exhibit a positive relationship as the 
better your ratings the lower interest rate you get on a loan.
*Homeonwers and borrowerrate also showed a relationship as more home owners recieved
lower interest rates compared to non homeowners. 

**A homeowner means they have a morgage on their credit profile which is good for the
Lender**

Besides the main variables used, I tried to establish relationships between the terms 
of the loan and the employment statuses of the borrowers. The regression plot showed that 
borrowers with 36 month terms recieved lower BorrowerRate (interest) as the loan amount
increases followed by 12 month term where loan amounts where lower and borrowers not that 
many too. I also noticed that employees and full time employees have better ProsperRatings 
which can influence their rates too.


## Key Insights for Presentation

For the presentation I focused on the influence of the other variables on the BorrowerRate,
which include Loan amount, prosper ratings and homeowners .

Below are the insights:
*I first started with Loan amount on the rate on a regression plot and soon realised that 
there was an inverse relationship there i.e as the loan amount decreases so does the 
interest rate. 
*I also used a regression line to understand the relation between Prosper 
ratings on Loan amount and interest rate and surprisingly realised that not all better 
borrowers recieved lower interest rates but rather borrower with ratings of (E) recieved
lower rates as loan increases. 
*Homweownership also showed an influence using the point plot where more homeowners 
recieved lower rates on their loans then non homeowners.