# Random Forest Project

For this project, we will be exploring publicly available data from LendingClub.com
. Lending Club connects people who need money (borrowers) with people who have money (investors). Ideally, as an investor, you want to invest in people who have shown a high likelihood of paying you back. Let's try to create a model that helps predict this.

Lending Club had a very interesting year in 2016, so we’ll take a look at some of its data with that context in mind. These data are from before the company went public.

We’ll use the loan data from 2007–2010 and try to classify and predict whether the borrower paid back their loan in full. You can download the data from here, or simply use the CSV file already provided. It is recommended to use the provided CSV file, as it has been cleaned of NA values.

Here’s what the columns represent:

credit.policy: 1 if the customer meets the LendingClub.com credit underwriting criteria, and 0 otherwise.

purpose: The purpose of the loan (possible values: "credit_card", "debt_consolidation", "educational", "major_purchase", "small_business", and "all_other").

int.rate: The interest rate on the loan (an 11% rate would be stored as 0.11). Borrowers deemed riskier by LendingClub.com are assigned higher interest rates.

installment: The monthly payment owed by the borrower if the loan is funded.

log.annual.inc: The natural log of the borrower’s self-reported annual income.

dti: Debt-to-income ratio of the borrower (amount of debt divided by annual income).

fico: The borrower’s FICO credit score.

days.with.cr.line: The number of days the borrower has had a credit line.

revol.bal: The borrower’s revolving balance (amount unpaid at the end of the credit card billing cycle).

revol.util: The borrower’s revolving line utilization rate (amount of credit used relative to total available credit).

inq.last.6mths: Number of inquiries made by creditors into the borrower’s credit in the last 6 months.

delinq.2yrs: Number of times the borrower has been more than 30 days past due on a payment in the past 2 years.

pub.rec: The number of derogatory public records for the borrower (bankruptcies, tax liens, or judgments).
