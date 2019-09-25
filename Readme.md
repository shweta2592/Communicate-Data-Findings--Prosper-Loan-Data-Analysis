
<h1><center>Prosper Loan Data Analysis</h1>

<h1> Installations </h1>

- Python 3
- Anaconda distribution to install Python, since the distribution includes all necessary Python libraries as well as Jupyter Notebooks.
- Numpy
- Pandas
- Matplotlib
- Seaborn

<h1> Project </h1>

The project is done on a dataset given by Prosper,which is America's first marketplace lending platform with over $7 billion in funded loans.This dataset consists of around 113937 records and 61 columns. IT consists of some main information like 'BorrowerAPR','EmploymentStatus,occupation,ProsperScore,ProsperRating,Homeowner,AvailableCredit,Delinquencies etc.

The main aim of our project is to establish a relarionship between the variables and what influences the variables the most.We use summary statistics and visualizations to discover relationships and patterns . As per the specifications, there are multiple visualizations carried out:

- Univariate visualizations
- Bivariate Visualizations
- Multivariate Visualizations

<h2> Summary of Findings

After analysis of different variables, some of the key observations were :

-  Majority of the people listed their occupation as 'others' followedby 'Professional'.
- Prosper Grade C receives maximum numberof ratings followed by B, A and D. Most of the BorrowerAPR for prosper rating C range between 0.17 and 0.27 with majority of them paying an interest between 20-25%.
- Another observation made was that majority of the listings stated their cause for taking the loan as 'Debt' which in macroeconomic sense is bad as they are creating a new debt for paying an old debt.
-  The BorrowerAPR(average) was at it's peak in the year 2011 and reduced to 18% in 2014(the lowest on an average).
- For High Current Delinquency accounts, the BorrowerAPR range between 30 to 35%.

<h2> Key Insights for Presentation </h2>

Histograms were created for numerical continuous variables and bar charts for categorical types. The histograms created for BorrowerAPR helped determine the distribution of the variable.
After exploring all the possible combinations with BorrowerAPR observed the below:
- CreditScore, AvailableBankCredit are positively correlated to ProsperScore and negatively correlated to BorrowerAPR
- Both CreditScore and ProsperScore are negatively correlated to Borrower APR which means if the Credit Score increases, Borrower APR decreases. Similar trend is followed by Prosper Score and Borrower APR.
