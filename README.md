# MachineLearningLab9
### Random Forest Project

In this project, we will analyze publicly available data from LendingClub. LendingClub operates as a platform that connects borrowers (individuals seeking loans) with investors (individuals willing to lend money). As an investor, the goal is to fund borrowers who are most likely to repay their loans. To support this decision-making process, we will build a predictive model that estimates the likelihood of loan repayment.

LendingClub experienced a notable period in 2016, which adds useful context when examining its data. However, for this project, we will focus on historical data collected before the company went public.

Specifically, we will use lending data from 2007 to 2010 to classify whether a borrower fully repaid their loan. The dataset (provided as a cleaned CSV file on Blackboard with no missing values) will be used to train and evaluate our model.

#### Column Descriptions

* **credit.policy**: Indicates whether the borrower meets LendingClub’s credit criteria (1 = yes, 0 = no).
* **purpose**: The reason for the loan (e.g., credit card, debt consolidation, education, major purchase, small business, or other).
* **int.rate**: The loan’s interest rate expressed as a decimal (e.g., 11% as 0.11). Higher rates generally reflect higher risk.
* **installment**: The monthly payment amount owed by the borrower.
* **log.annual.inc**: The natural logarithm of the borrower’s reported annual income.
* **dti**: Debt-to-income ratio, calculated as total debt divided by annual income.
* **fico**: The borrower’s FICO credit score.
* **days.with.cr.line**: The number of days the borrower has maintained a credit line.
* **revol.bal**: The borrower’s outstanding revolving balance.
* **revol.util**: The percentage of available credit currently being used.
* **inq.last.6mths**: Number of credit inquiries in the past six months.
* **delinq.2yrs**: Number of times the borrower was over 30 days late on payments in the last two years.
* **pub.rec**: Number of negative public records (e.g., bankruptcies, tax liens, or legal judgments).
