# Bank-Loan-Report-Data-Analysis
This project provides an interactive Power BI dashboard for analyzing bank loan data, offering insights into loan applications, funding, repayments, and borrower profiles. It enables financial institutions to track overall loan performance, monitor default risks, and evaluate trends by state, loan purpose, and borrower attributes.

# Project Objective

The objective of this project is to develop a data-driven dashboard that helps the bank monitor and evaluate loan performance metrics. It focuses on understanding total loan applications, funded and received amounts, interest rates, and debt-to-income ratios. The goal is to support better financial decision-making by identifying good vs. bad loans and key patterns in borrower behavior.


<a href="https://github.com/DeepakfromSIT/Bank-Loan-Report-Data-Analysis/blob/main/financial_loan.csv">Dataset Used</a>

# Business Questions / KPIs

<h2>Business Questions:</h2>
What is the total number of loan applications, and how much has been funded and received?
What percentage of loans are classified as good vs. bad?
How do funded amounts vary by state, purpose, and borrower characteristics?
Which loan terms and home ownership categories contribute most to funding?
What is the overall loan performance in terms of repayment and interest rate trends?

<h2>Key Performance Indicators (KPIs):</h2>
Total Loan Applications (38.6K)
Total Funded Amount ($435.8M)
Total Amount Received ($473.1M)
Average Interest Rate (12%)
Average DTI (13.3%)
Good Loan Percentage (86.2%)
Bad Loan Percentage (13.8%)

<img width="1343" height="798" alt="Screenshot 2025-10-08 203629" src="https://github.com/user-attachments/assets/4c0b881d-8dbe-4510-9e2b-5ae6b7d3efe3" />


# Process

<h3>Data Collection:</h3>Imported raw loan data containing details such as loan status, funded amounts, interest rates, and borrower information.

<h3>Data Cleaning & Transformation:</h3>Removed duplicates and missing entries.
Standardized date formats and numeric fields.
Categorized loans as Good or Bad based on repayment status.

<h3>Data Modeling:</h3>Established relationships between tables (Loan, Borrower, State, etc.).
Created calculated measures for KPIs using DAX.

<h3>Dashboard Development (Power BI):</h3>Designed three pages: Summary, Overview, and Details.
Integrated slicers for dynamic filtering by state, grade, purpose, and loan type.
Added visuals such as donut charts, maps, bar charts, and line trends.

<h3>Insights Extraction:</h3>Compared loan performance across months, regions, and borrower profiles.

<h2>Dashboard Interaction</h2> <a href="https://github.com/DeepakfromSIT/Bank-Loan-Report-Data-Analysis/blob/main/Bank%20loan.pbix">View Dashboard</a>

# Final Conclusion

* A total of 38.6K loan applications were processed, with $435.8M funded and $473.1M received.

* Good loans accounted for 86.2%, reflecting strong repayment performance.

* Bad loans represented 13.8%, signaling moderate credit risk.

* The average interest rate stood at 12%, with an average DTI of 13.3%, indicating manageable borrower debt.

* Mortgage and rent loans dominated the portfolio, while debt consolidation was the top loan purpose by amount funded.

* Employee tenure and state location significantly influenced total funded amounts, with the highest funding coming from borrowers with 10+ years of experience.

This dashboard empowers bank stakeholders to track loan performance, minimize default risks, and make data-driven lending decisions.
