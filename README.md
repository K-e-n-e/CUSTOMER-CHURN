## Customer Churn Analysis (Excel Dashboard)

An Excel analysis and dashboard exploring why customers leave a telecom company, Databel, and which customer groups are most at risk.

## Business Problem

Databel is losing customers, and retaining an existing customer costs far less than acquiring a new one. This project answers:

<p>How many customers are leaving, and what is the overall churn rate?</p>
<p>Which customer segments (contract type, age group, payment method, tenure, and so on) churn the most?</p>
<p>Why do customers say they are leaving?</p>

## Dataset

The workbook contains data on 6,687 customers, with details on:

<p>Demographics: gender, age, state, age group (Under 30, Senior, Other)</p>
<p>Account: tenure in months, contract type, payment method, monthly and total charges</p>
<p>Services: international plan, unlimited data plan, device protection and online backup, monthly GB downloaded</p>
Behaviour: local and international calls and minutes, customer service calls
<p>Churn: churn label, churn category, and churn reason</p>

## Approach
<p>Loaded and reviewed the customer data in Excel.</p>
<p>Created helper columns with formulas, such as a binary churn flag, age groups (Under 30, Senior, Other), and data usage groups (less than 5 GB, 5 to 10 GB, 10 GB or more).</p>
<p>Built PivotTables to calculate churn rate across each customer segment.</p>
<p>Visualised the results with PivotCharts.</p>
<p>Combined the key metrics and charts into an Overview dashboard.</p>

## Dashboard
<img width="1822" height="729" alt="image" src="https://github.com/user-attachments/assets/61c03405-865f-4cd7-93f4-255caa5b5480" />

## Key Findings
<p>Overall churn rate is about 26.9%. 1,796 of 6,687 customers churned.</p>
<p>Contract type is the strongest driver. Month-to-month customers churn at about 46%, compared with about 11% on one-year contracts and under 3% on two-year contracts.</p>
<p>New customers are the most likely to leave. Customers in their first 12 months churn at about 48%, falling to about 10% for those with more than 4 years of tenure.</p>
<p>Seniors churn more. Senior customers churn at about 38%, compared with about 24% for non-seniors.</p>
<p>Customer service calls are a warning sign. Customers with 3 or more service calls churn at nearly 90% or higher, compared with about 9% for those who never called.</p>
<p>Payment method matters. Direct debit (about 35%) and paper check (about 38%) customers churn far more than credit card customers (about 15%).</p>
<p>Unlimited data plan customers churn more, at about 32% compared with about 16% for those without it.</p>
<p>Competitors are the main reason for leaving. Of the customers who churned, 805 cited a competitor, mainly because of a better offer or better devices.</p>

## Recommendations
<p>Offer incentives to move month-to-month customers onto longer contracts.</p>
<p>Focus retention efforts on customers in their first year.</p>
<p>Treat repeated customer service calls as an early warning and follow up quickly with those customers.</p>
<p>Review the unlimited data plan, since its customers churn at twice the rate of others.</p>
<p>Run targeted retention offers for senior customers and encourage credit card payments.</p>
<p>Review competitor offers and device options to stay competitive.</p>

## Tools Used
<p>Microsoft Excel (PivotTables, PivotCharts, formulas, dashboard design)</p>

    
## About

Completed as a portfolio project to practise data analysis and dashboard building in Excel.
