# PhonePe Data Analysis - Interactive Power BI Dashboard

##  Project Overview
This project is an end-to-end Power BI dashboard designed to analyze transaction data for PhonePe, a leading digital payments app. The interactive report provides a comprehensive overview of user transactions, payment statuses, and detailed breakdowns of four core app services: Insurance, Loans, Money Transfer, and Recharge & Bills. 

A critical objective of this dashboard is tracking transaction success rates and identifying the root causes of payment failures—a crucial KPI for retaining users and maintaining platform reliability.

##  Key Features
*   **Interactive Filtering:** Dynamic date range slicers applied across all dashboard pages to track performance over specific time periods.
*   **Comprehensive KPIs:** Top-level metrics tracking Total Transaction Amount, Total Transactions, Successful Transactions, and Failed Transactions.
*   **Failed Payment Analysis:** A dedicated breakdown of payment failure reasons, including Server Errors, Wrong PIN, Insufficient Balance, Wrong Info, and Bank Denied.
*   **Time-Series Trends:** Visualizing the amount transacted versus the month to identify seasonal trends or peaks.
*   **Custom Page Navigation:** Interactive UI buttons that allow seamless navigation between the overarching Home summary and the detailed individual service pages.

##  Dashboard Structure
The report is structured into five dedicated pages:
1.  **Home Page:** A collective summary of the entire project, displaying total amounts, overall transaction success/failure ratios, and cross-service comparisons.
2.  **Insurance:** Tracks premium amounts and total transactions across Term Life, Car, Bike, and Health insurance policies.
3.  **Loans:** Analyzes loan amounts and transactions divided into Gold Loans, Auto Loans, Mutual Funds, and Credit Scores.
4.  **Money Transfer:** Details transactions sent to mobile numbers, QR codes, self-accounts, and UPI IDs.
5.  **Recharge & Bills:** Tracks activity across Cable TV, DTH, Fastag, and Mobile recharges.

##  Data Structure
The dataset contains up to 300,000 rows of transactional data and is structured into six key tables:
*   **All Users:** User ID, Name, Age, and Joining Date.
*   **All Transactions:** A consolidated master table used for the Home page, detailing Transaction IDs, Amounts, Service Types, Payment Statuses, and Dates.
*   **Individual Service Tables:** Dedicated tables for Insurance, Loans, Money Transfer, and Recharge & Bills containing specific sub-service types.

##  Tech Stack & Skills Demonstrated
*   **Tool:** Power BI
*   **Techniques:** Data Modeling, DAX (Count Distinct, Sum, filtering logic), Interactive Visuals (Line charts, Pie charts, Bar graphs), and custom UI/UX design (Page navigation buttons, grouping, dynamic formatting).
*   **Design:** A custom purple-themed aesthetic designed to match the PhonePe brand identity.

##  Business Value
For fintech and payment applications, monitoring transaction status is a 100% focus area. Millions of users experiencing recurring failed payments will quickly abandon an app for alternatives. This dashboard acts as an indicator and tracking tool to provide prompt responses to technical errors (like server drops) and user-end errors (like insufficient funds), driving strategic improvements.

