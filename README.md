#### DATASET
The dataset used to carry out several exploratory data analysis and visualizations is the Prosper Loan dataset downloaded through a link provided by Udacity. The dataset contains listings from 2005 to 2014 which includes 113,937 observations with 81 variables like loan amount, borrower rate (or interest rate), current loan status, borrower income and many others.             
To explore this dataset, I had to first do some data cleaning which resulted to a change in the structure (111,936 observations, and 83 variables). Then I went on to make some findings on the dataset.

#### SUMMARY OF FINDINGS
Through the help of some libraries (Seaborn, Pandas, Matplotlib), several data visualizations were carried out to get answers to questions made.
- Current and completed listings constitutes over 70% of the total listings (This insight will be covered in the explanatory presentation)
- Out of all the credit grades, 'C' is the most common with a proportion of 21%
- Most listings have an Income range within 25,000-74,999 dollars
- In 2013, the highest number of listings was created, while the lowest number of listings was created in 2009
- Most listings fall under the category of people whi have a job (employed, full-time, and self-employed)
- The proportion of home owners and non home owners are approximately equal
- Aside "Others", the top occupation of borrowers are Computer Programmer, Professional, Executive, and Teacher
- About 35% of borrowers come from California, Texas, Florida, and New york
- Debt Consolidation is the most common listing category with about 50% of the total listings
- The lower the credit grade,  the more likely for borrowers to default
- A borrower is more likely to default if their listing category is "Not Available"
- Listings that have Employment Status as "Not Available" are more likely to default
- Current listings have the highest sum of original loan amount of over 500 million dollars
- There is a strong positive relationship between Interest rate and Lender's yield (This insight will be covered in the explanatory presentation)
- Less than 10 listings have a borrower rate (interest rate) of 0
- There is a normal distribution of borrower rates in 2005, 2006, 2007, 2008, 2009, and 2013 (This insight will be covered in the explanatory presentation)
- The yearly sum of borrower rates for each employment status changes with time (This insight will be covered in the explanatory presentation)

#### KEY INSIGHTS FOR PRESENTATION
- To weigh the effectiveness of Prosper's risk management system, I'd like to check if most of their listings have been either defaulted or charged-off. For this, I chose the insight "Current and Completed listings constitutes over 70% of the total listings". This concludes that Prosper Loan company has a very good risk management system.
- To check for a strong relationship between variables, I chose the finding "There is a strong positive relationship between BorrowerRate and LenderYield"
- To know how interest rate is distributed throughout the years: "There is a normal distribution of borrower rates in 2005, 2006, 2007, 2008, 2009, and 2013"
- To see the changes in the annual sum of borrower rates for each employment status: "The yearly sum of borrower rates for each employment status changes with time"
