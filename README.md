# Exploratory Data Analysis - Loan-Investment-Case-Study
<img src = “https://github.com/ravichan18/images/blob/main/EDA_LoanInvestment.jpeg” width = "1000"/>

# Scope
This project is about consumer finance company which specialised in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.

The data given below contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

When a person applies for a loan, there are two types of decisions that could be taken by the company:

Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

Fully paid: Applicant has fully paid the loan (the principal and the interest rate)

Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.

Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)

# What is Exploratory Data Analysis
Exploratory Data Analysis (EDA) is the process of exploring, investigating and gathering meaningful insights and nuggets using different kind of statistical measures and visualizations. The objective of EDA is to develop an understanding of data by uncovering trends, relationships and patterns.

When it comes to the requirement of statistical knowledge, visulaization technique and data analysis tools like Numpy, Pandas, Matplotlib, etc. we categories it as an art. When there is reqirement of asking interesting questions to guide the investigation for generating meaningful insight we call it a science. So it is a mixture of both art and science.
