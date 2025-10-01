# Project Name
This project's goal is to understand the strategy of Finance company which specalises in lending loans. Using Python's libraries and EDA, the code analysis the data and presents the understanding of borrowers, loan amounts, different kind of interest rates offered, company risk strategy etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- The project is based on a Finance company that lends loans to its urban customers. As a business, the company's biggest challenge lies in weighing the risks while achieving growth. How to 
figure out if the borrower is creditworthy and approve the loan and how to pick out risky borrowers from the huge number of loan applicants. Hence the data-driven approach is best to solve this.

- Business Problem. 

The company wants to identify risky applicants and understand the factors that drive loan defaults.

    1. Seperating high-risk applicants from reliable borrowers and avoid lending them the loan
    2. Optimize interest rates and loan terms based on applicants risk profile.
    3. Understand the reasons for loan default and then filter the customer pool accordingly.

- Dataset Information. 

The loan.csv has the information on past applicants. To name the important variables used in the analysis
    1. Loan factors - Loan amounts, loan status, grade, 
    2. Consumer details - Grade, Debt-to-income ration, annual income
    2. Loan Status - Charged off or fully paid 


## Conclusions
- Conclusion 1. 
**Loan Status distribution.**. 

Majority of applications paid their loans in full.
- Conclusion 2. 
**Interest Rate w.r.t Loan Status.**. 

Boxplot between loan status and interest rate reveals that people who defaulted on loan had higher interest rate 
This indicates that risky parties are being charged higher interest rate compared to non-risky ones who fully pay their loans off.
- Conclusion 3. 

Low Grade applicants (e,f,g) had much higher default rates compared to higher grades (a,b). So company's grade system is working as expected
- Conclusion 4. 
**Debt-to-Income Ratio.**. 

Distribution of DTI showed that very high DTI values are uncommon, but applicants with  high DTI still show a greater tendency to default. This suggests DTI is a strong predictor of repayment ability.


## Technologies Used
- python - version 3.9.6
- seaborn - version 0.13.2
- matplotlib - version 3.9.4
- pandas - version 2.3.1

