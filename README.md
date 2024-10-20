# Project Title:- Analysis of Fincorp Lending Data to Evaluate the Lending Process/Fraud Detection and Improve it's Market Offerings

### Project Context:- 

A financial corporation, Fincorp Lending, provides various types of loans such as personal, auto, home, education, and business loans. The corporation operates across multiple regions and caters to a diverse clientele. With a competitive market and regulatory challenges, efficient loan processing and risk management are crucial. 

### Business Problem:-
 
The corporation faces challenges in managing loan defaults and optimizing loan approvals. High default rates have financial implications and reduce profitability. Additionally, high NPAs and financial fraud/mismanagement is likely to jeopardise the financial position and operation ability he firm. 

### Tools/Software:-Power BI and Microsoft PowerPoint

### Tasks/Objectives:-

1) Perform basic data cleaning, standardize data formats using Power Query, calculate total loans, average interest rates, basic loan statistics using DAX

2) Tailor loan products effectively and identify profitable customer segments.

3) Categorize customers based on loan application; visualize the segments with complex charts.

4) Time-Series Analysis, forecasting, and trend identification for loan applications across the loan types.

5) Reduce the rate of loan defaults by improving the credit risk assessment model (Understanding the NPAs and detect the potential likeliness of fraud in the loan approval process)

### Key Findings:- 

1) On an average the firm approved 4 loans to a single borrower, which is likely to create a high NPA situation over the long term.

2) There are a total of 6,729 borrowers who received approximately 2 loan approvals with credit_score classified as bad (<400) and worst(<200), thereby creating a high risk scenario.

3) Furthermore, out of the above 6,729 borrowers 4,471 borrowers are considered as defaulters, that have either defaulted the previous loans and never settled the loan amount. The firm gave around 6,099 loans to these 4,471 borrows making it very high risk business. 

4) The average monthly income of these 4,471 borrowers remained as 9,0150.0 Rs and the monthly installment they require to pay for all the loans combined remains at 9,120.0 Rs Due to which, the monthly outstanding loan installment amount remained at -664.8 Rs. on an average.

5) Finally, out of the given 6,099 loans a total of 4,082 loan accounts are expected to become NPAs and 3,295 borrowers holding these loan accounts have not paid monthly installment.

6) As such high discrepancy at loan approval stage is not acceptable in financial sector, there is a need to scrutinize the loan approval process of 3,295 borrowers to understand the extent of fraud.

### Data Description/Data Dictionary:- 

1) Loan ID: A unique identifier for each loan.
2) Issue Date: The date on which the loan was issued.
3) Loan Type: The category of loan (Personal, Auto, Home, Education, Business), which affects the risk and terms of the loan.
4) Loan Amount: The total amount of the loan issued.
5) Interest Rate (%): The interest rate charged on the loan, influencing the monthly payments and the total cost of the loan to the borrower.
6) Term (months): The duration over which the loan will be repaid, affecting the loan's affordability and the total interest paid.
7) Loan Status: Current status of the loan (Approved, Rejected, Pending), indicating the outcome of the loan application.
8) Customer ID: A unique identifier for each customer.
9) Region: The geographical region of the borrower, which might influence the loan conditions and default rates due to economic factors.
10) Payment Status: Current payment status (Paid, Unpaid, Delinquent), crucial for monitoring defaults and financial health.
11) Monthly Payment: The amount the borrower needs to pay each month, directly impacting the borrower’s payment behavior.
12) Customer Age Group: The age category of the customer, which might correlate with the loan amount, type, and risk profile.
13) Employment Status: Indicates whether the borrower is employed, self-employed, or unemployed, affecting their ability to repay the loan.
14) Annual Income: The yearly income of the borrower, a critical factor in determining loan eligibility and risk.
15) Credit Score: A numerical expression based on a level analysis of the borrower's credit files, predictive of the likelihood to repay 16) the loan.
17) Number of Dependents: Number of individuals financially reliant on the borrower, impacting their financial stability.
18) Previous Loan Amount: Amount of the most recent loan taken by the borrower, providing insights into the borrower’s debt history.
19) Previous Loan Status: Status of the borrower’s most recent loan (Paid Off, Defaulted), important for assessing credit risk.
20) Housing Status: Indicates whether the borrower owns a home, rents, or lives with parents, which can affect their financial stability and creditworthiness. 
