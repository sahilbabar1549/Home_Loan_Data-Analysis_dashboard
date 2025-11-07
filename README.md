# Home_Loan_Data-Analysis_dashboard
<img width="936" height="736" alt="Screenshot 2025-11-07 124319" src="https://github.com/user-attachments/assets/824c1e5c-86ea-4256-a4ee-959a568aeacd" />


## Project Overview
This project uses the Home Loan dataset to analyze customer applications, approval patterns, and financial performance related to home loan processing. Using Microsoft Power BI, the goal is to evaluate approval rates, loan amount distribution, applicant demographics, and key financial indicators to improve business efficiency and decision-making in the loan approval process.
________________________________________
## Dataset Description
The dataset contains detailed information about applicants, their financial background, and loan outcomes, including:
•	Applicant Details: Gender, Marital Status, Education, Dependents, Self-Employment.
•	Financial Data: Applicant Income, Co-applicant Income, Loan Amount, Loan Term.
•	Loan Information: Credit History, Property Area, Loan Status (Approved/Rejected).
This data provides a holistic view of loan performance across demographic and financial variables.
________________________________________
## Business Objectives
The primary objectives of this BI analysis are:
•	Identify key factors influencing loan approvals.
•	Analyze income and loan amount relationships by demographic categories.
•	Study credit history impact on approval probability.
•	Compare loan approval rates across property areas and genders.
•	Develop interactive dashboards to allow management to explore data across multiple filters.
________________________________________
## Tools & Techniques
Microsoft Power BI
•	Data Cleaning & Transformation:
o	Used Power Query to remove blanks, fix inconsistent labels, and convert data types.
o	Replaced missing values in Loan Amount and Credit History.
•	DAX Measures Created:
o	Total Disbursed Amount = SUM('Sanction Data'[Disb Amt in Lacs])
o	Total Loan Applied = SUM('Sanction Data'[Applied Loan Amount in Lacs])
o	Total Sanctioned Amount = SUM('Sanction Data'[Sanction Amt in Lacs])
o	Total Recovered Amount = SUM('Recovery Data'[Recovery Amount])
o	Total Customer = COUNT(Customer[Customer Number])

##	Visuals Used:
o	Donut Chart: Approval vs. Rejection ratio.
o	Bar Chart: Loan approvals by property area and gender.
o	Stacked Column Chart: Education and self-employment impact on loan status.
o	Card Visuals: Total Applications, Approval %, Average Income, and Average Loan Amount.
o	Filters/Slicers: Gender, Property Area, Education, and Credit History.
________________________________________
 ## Deliverables
•	Cleaned Power BI dataset with transformed fields.
•	Interactive Home Loan Dashboard summarizing insights visually.
•	Key performance indicators (KPIs) for approval rate and financial metrics.
•	Word-based summary report (this document).
________________________________________
 ## Key Insights
•	Applicants with a positive credit history had over 80% approval rate.
•	Urban property areas showed higher loan approval frequency.
•	Graduate applicants had higher approval chances compared to non-graduates.
•	Self-employed individuals tended to apply for higher loan amounts, with slightly lower approval rates.
________________________________________
 ## Future Enhancements
•	Predictive Analytics: Implement Power BI or Python forecasting models to predict loan approval likelihood based on applicant profile.
•	Risk Scoring Model: Develop a credit-risk scoring KPI combining income, loan amount, and credit history.
•	Geographical Expansion: Add map visuals showing loan distribution by city or state.
•	Time-based Analysis: Include year/month fields to track approval trends over time.
•	Integration with Power Automate: Automate monthly loan performance reports for business users.

