# Data Visualization - Project: Communicate Data Findings 
## by Karthick Mahalingam


## Loan Data for Prosper

This dataset contains list of loans and each loan has about 81 variables to describe the loan details. Of these 81 fields, we have identified the below fields for our analysis.

* Borrower's State.
* Loan Amount.
* Borrower's Occupation.
* Loan Listing Category.
* Loan Creation Date.
* Annual Percentage Rate (APR) of the Loan.
* Borrower

## Summary of Findings

*  Highest number of loan applications came from the state of California. About 13 percent of loan applications came from California. Next State, Texas has about 6 percent of the loan application.
* Least Number of applications came the state of North Dakota, which had only 50 applications (less than 0.0005 percent of total application proportion ) from the year 2007 to 2014. [Note: Not Included in the Explanatory Slides]
* More than 60 percent of the loan activities are originating from South and West part of the US regions.
* Borrower's Credit Rating and their loan application follow a NORMAL DISTRIBUTION with highest loan applications are from borrower whose credit rating is 'C' [Note: Not Included in the Explanatory Slides]
* Loan Original Amount follows MULTI-MODAL DISTRIBUTION, with peaks of original loan amount at 3K-5K USD, 10K USD, 15K USD, 20K USD, 25K USD. After log transformatio, the distribution looks slightly right skewed with peaks at 2.5K-5K USD, 9K-15K USD.  [Note: Not Included in the Explanatory Slides]
* 'Debt Consolidation' is one of the main reason for the loan request, while recreational loans like 'RV', 'Boat' and green loans are at the lower end.
*  'Professional' community(Borrower's occupation) tend to borrow a lot when compared to other occupations.
* From the year 2007 to 2008, borrowing increased by 0.3%. But the during the Great Recession period (2008-2009), the borrowing dropped by 85 percent. This could be the result of feared investors during the great recession period. Once the recession period ended (after the year 2009), the borrowing activity increased drammatically.
* All the loan which are in GOOD STATE (i.e. Loan Status like Completed,Current,Cancelled,FinalPayInProgress ) has mean annual percentage rate below 0.21 percent. [Note: Not Included in the Explanatory Slides]
* All the loan which are in BAD STATE (i.e. Loan Status like ChargedOff,Defaulted,Past Due ) has mean annual percentage rate above 0.21 percent. [Note: Not Included in the Explanatory Slides]
* It seems if the mean annual percentage rate is greater, its possible, they could go into BAD STATE. [Note: Not Included in the Explanatory Slides]
* For the state of California, top five borrower's occupations are Executive, Sales, Professional, Administrative Assistant, and Programmer.Executive tends to borrower higher loan amount when compared to other professions. This could because, they might be earning more money compared to others.
*  For the state of California, top five loan reasons are for: 'Home Improvement', 'Debt Consolidation', 'Business', 'Auto', 'Personal Loan'.Loan Amounts borrowed for 'Home Improvement', Debt Consolidation', 'Business' are higher than 'Auto', 'Personal Loan', as the higher amount distribution for 'Auto' and 'Personal Loan' are very few. Number of Loan applications with lower loan amount is for 'Auto', 'Personal Loan' reasons.
* There is strong negative relationship between Prosper Score and APR of the loan. This makes sense, as borrower's poor credit rating results in high APR for the loan. There is strong negative relationship between Credit Score and APR of the loan. This also makes sense, as borrower's credit score results in high APR for the loan. [Note: Not Included in the Explanatory Slides]
* Also relations between other features show weaker signs. For instance, there is a weak relationship between the APR of the loan and loan original amount.[Note: Not Included in the Explanatory Slides]
* Executives, Sales Personnels, Admin. Assistants, and Computer Programmer tend to follow the same trend. ie. the number of loan application counts over the period from 2006 to 2014 are similar. But Professionals' application count expontentially increased.

## Key Insights for Presentation

* First, We identified the US State which had high distribution of the loan applications.
* After that, State of California is chosen for further analysis, as it had the highest number of loan applications.
* Focused on whose is borrowing (i.e. Occupation of the Borrower) and for what reasons they are applying for loans.
* Calculated the trend of loan amount involved before and after recession.

Above points helped tell the story of the loan trends.