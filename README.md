# Prosper Loan Data Exploration
## by Adebajo Ruth Oluwadamilola

## Dataset

Loan Data from Prosper, provided by Udacity. It was downloaded using the link; https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud651/prosperLoanData.csv&sa=D&ust=1581581520570000 . This dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.

I performed data wrangling on the data to check how tidy and clean the data was. The data wasn't so  untidy as each row was an observation and each column was a variable. There were no duplicates. columns like Credit grade and prosperRating (Alpha) needed to be joined. Some datatypes were not correct and there were so many missing values.I picked the variable of interest and picked variables thet would be necessary in the analysis. I cleaned the data while making sure not to lose so many data. 

## Summary


I made exploratory analysis on distribution of all the features I picked, I checked the distribution of all the variables and Their distribution in relation to themselves,I found that percentfunded variable had very weak correlations with other variables and this is because most of the loan observations had PercentFunded of 1.0.

Exploring the distribution of univariables of interest, one of the insightful information discovered was that CA State has the highest borrowers. Looking at Borrower's employment status, I discovered majority of the borrowers have either employed or fulltime employment status. Investigating further into their source of income, I discovered that their income mostly ranges from 25,000-74,999 and their monthly income distribution is skewed to the right and they are usually less than 30k. Their income ratio is right skewed as well.
Further into Bivariance exploration,to observe the relationships between 2 variables each of the data, I discovered that there was a high correlation between 'Recommendations'and 'friends that invest' with Little to no correlation between LenderYield and PercentFunded
Lastly on Multivariant exploration, 
- There is a strong relationship between CurrentlyInGroup and lenderYield when plotted with PercentFunded
- There is a strong relationship between CreditScoreRange and lenderYield when plotted with PercentFunded
- There is a strong relationship between MonthlyLoanPayment and lenderYield when plotted with PercentFunded

## Key Insights for Presentation

For the presentation, I focused on showing variation in variables with percent funded and derive characteristics of loan observations with percentFunded
Then, I checked variaton of categorical data and some numerical data with percentFunded. I used boxplots to check the relationship between categorical data and percent funded and I was able to observe pattern I stated in the explanatory visualiztion slide.
For the numerical data and some categorical, I used a scatterplot and plotted with lenderyield and percentfunded to get more insights and stated the pattern observed in the slide.
