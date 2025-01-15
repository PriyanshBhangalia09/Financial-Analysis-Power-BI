# Financial-Analysis-Power-BI
## Project Overview
As a Financial Data Analyst, this project aims to analyze credit card usage and financial metrics for a banking institution. The analysis involves calculating financial KPIs using **DAX formulas** in Power BI. These KPIs assess customer behavior, credit utilization, and delinquency risk, providing actionable insights to improve customer retention and financial performance.

---

## Objectives

### DAX Calculations Implemented:
1. **Running Total of Credit Card Transactions:**
   Calculate the cumulative sum of credit card transaction amounts over time.

2. **4-Week Moving Average of Credit Limit:**
   Compute the 4-week moving average for `Credit_Limit` for each client.

3. **Month-over-Month (MoM%) and Week-over-Week (WoW%) Growth:**
   Determine the growth rates for `Transaction_Amount` over months and weeks.

4. **Customer Acquisition Cost (CAC):**
   Calculate CAC as a ratio of `Transaction_Amount`.

5. **Yearly Average of Avg Utilization Ratio:**
   Compute the yearly average of `Avg_Utilization_Ratio` for all clients.

6. **Percentage of Interest Earned Compared to Total Revolving Balance:**
   Calculate the percentage of `Interest_Earned` relative to `Total_Revolving_Bal` for each client.

7. **Top 5 Clients by Total Transaction Amount:**
   Identify the top 5 clients based on their total transaction amounts.

8. **High Utilization Clients:**
   Flag clients whose `Avg_Utilization_Ratio` exceeds 80%.

9. **Customer Churn Indicator:**
   Create a KPI to flag clients who have not made any transactions (`Total_Trans_Amt = 0`) in the last 6 months.

10. **Delinquency Rate:**
    Calculate the percentage of clients with `Delinquent_Acc > 0`.

11. **Credit Risk Score:**
    Create a score for each client based on their `Avg_Utilization_Ratio`, `Delinquent_Acc`, and `Total_Revolving_Bal`.

12. **Income vs Credit Limit Correlation:**
    Show the correlation between `Income` and `Credit_Limit` for all clients.

13. **Average Customer Satisfaction Score by Credit Card Category:**
    Calculate the average `Cust_Satisfaction_Score` by `Card_Category`.

14. **Loan Approval vs Credit Limit:**
    Analyze how `Credit_Limit` affects personal loan approval by calculating the average credit limit for clients with and without loans.

15. **High Risk Clients Flag:**
    Flag clients whose `Total_Revolving_Bal` exceeds 90% of their `Credit_Limit` and who have a high `Avg_Utilization_Ratio`.

---

## Features
- **Customer Behavior Analysis**: Identify patterns in credit utilization and transaction activity.
- **Delinquency Risk Assessment**: Measure the percentage of delinquent accounts and highlight high-risk clients.
- **Financial Insights**: Understand the correlation between financial metrics like income, credit limit, and loan approvals.
- **Customer Retention Metrics**: Track active customers and identify potential churn risks.
- **KPI Creation**: Leverage DAX to create actionable KPIs for performance tracking.
