# 🏦 Banking Analytics Dashboard
### Power BI | Data Analytics Portfolio Project



## 📌 Project Overview

This project is a multi-page **Banking Analytics Dashboard** built in Power BI, analysing customer behaviour, loan performance, transaction activity, and account balance distribution for a Nigerian retail bank.

The dataset covers **3,011 customers** across **22 cities in Nigeria**, spanning account records from **1955 to 2023**, with a total of **₦984 billion in loans** and **₦76.59 million in transactions**.



## 📊 Dashboard Pages

### 1. Customer Profile Summary
A high-level view of the bank's customer base — who they are, where they are, and how much they hold.

**Key Metrics**
- 🧑‍🤝‍🧑 Total Customers: **2,923**
- 💰 Total Bank Deposits: **₦2 billion**
- 🏦 Total Savings Accounts: **₦704.18 million**
- 📅 Average Customer Age: **51 years**

**Insights**
- Gender split is nearly equal: **50.7% Female, 49.3% Male**
- **Lagos** dominates customer concentration, followed by Abuja and Imo
- The **51+ age group** is the largest customer segment — indicating a mature, established customer base
- Structural Analysis Engineers and Database Administrators are among the highest-value occupation segments by bank holdings

**Recommendations**
- The dominance of the 51+ age group signals an ageing customer base. The bank should introduce targeted products — such as youth savings accounts, student loans, and digital-first services — to attract and retain the 18–35 demographic before competitor banks capture that segment
- With Lagos accounting for a disproportionate share of customers, the bank should develop a geographic expansion strategy focusing on underleveraged states like Kebbi, Zamfara, and Sokoto, where banking penetration is historically low
- Since gender distribution is balanced, marketing campaigns should be equally segmented by gender with tailored messaging, particularly around savings products where female customers may show different behaviour patterns





### 2. Loan Analytics
A breakdown of the bank's loan portfolio — who borrows, how much, and how lending compares to deposits.

**Key Metrics**
- 💳 Total Bank Loans: **₦985.83 billion**
- 👥 Number of Loan Customers: **300**
- 📊 Average Loan per Customer: **₦3.29 billion**

**Insights**
- Only **~10% of customers** (300 out of 3,011) hold loans — a low loan penetration rate
- The **51+ age group** accounts for the highest loan uptake, followed by the 18–25 bracket
- **Lagos and Kano** have the highest loan-to-deposit ratios by city
- Recruiters and Office Assistants rank among the top occupations by total loan value — suggesting loan access is broad across income levels

**Recommendations**
- A 10% loan penetration rate is critically low for a retail bank of this size. The bank should launch a targeted loan awareness campaign — especially promoting personal loans, SME loans, and salary advance products to the 90% of customers currently not borrowing
- The high loan uptake among the 51+ group presents a credit risk concern. A risk-tiered lending policy should be introduced, with stricter affordability assessments for older borrowers and incentivised early repayment schemes
- The 18–25 segment shows loan appetite despite being a smaller group — the bank should introduce micro-loan or graduate loan products with flexible repayment terms to capture and nurture this segment long-term
- Cities like Lagos and Kano with high loan-to-deposit ratios may be approaching credit stress. The bank should monitor these markets closely and consider deposit mobilisation campaigns in those cities to rebalance the ratio




### 3. Transaction Trends
An analysis of how customers move money — the volume, methods, timing, and value of transactions.

**Key Metrics**
- 💸 Total Transaction Value: **₦76.59 million**
- 🔢 Total Transactions: **3,000**
- 📈 Average Transaction Value: **₦25,531**
- 🏆 Highest Single Transaction: **₦75,963**

**Insights**
- **Money Transfers** are the most common transaction type (712 transactions, 23.7%), followed by Money Deposits (630, 21%)
- **Bank channels** handle the most volume (777 transactions), followed closely by Mobile banking (688) — showing strong digital adoption
- Transaction volume is relatively even across all time periods (Morning, Afternoon, Evening, Night), with a slight peak in the Evening
- Transaction value peaked around **March–April** and declined steadily through the second half of the year

**Recommendations**
- Mobile banking is already at 688 transactions and closing the gap with branch banking. The bank should accelerate mobile app investment — adding features like instant transfers, bill payments, and loan applications — to fully shift volume off expensive branch infrastructure
- The sharp post-April decline in transaction value suggests seasonality driven by early-year salary cycles or tax periods. The bank should introduce Q3/Q4 incentive programmes such as cashback on transfers or zero-fee months to sustain transaction volume in the second half
- With Evening being the peak transaction period, the bank's customer support and system uptime SLAs should be optimised for evening hours to reduce failed transactions and improve customer satisfaction
- Informal Services (200 transactions) still account for a notable share of transaction mediums — indicating some customers prefer unstructured channels. The bank should investigate this segment and design agent banking or USSD solutions to formalise and capture these transactions

### 4. Account Balance Distribution
An overview of how balances are distributed across account types, cities, and account officers.

**Key Metrics**
- 🏛️ Total Accounts: **2,998**
- 💼 Total Opening Balance: **₦4 trillion**
- 📊 Average Opening Balance: **₦1.26 billion**
- 🔝 Max Opening Balance: **₦5.22 billion**

**Insights**
- **Domiciliary accounts** hold the highest total opening balance, followed by Current accounts
- The majority of customers fall in the **₦500M+** balance range, skewing wealth distribution to a smaller high-value segment
- **Paul Holmes** and **Jonathan Hawkins** are the top-performing account officers by average managed balance
- Account openings have been relatively consistent since the **1960s**, with a notable uptick post-2000

**Recommendations**
- Domiciliary accounts dominating the balance sheet signals that high-net-worth customers prefer forex-denominated holdings, likely as a hedge against naira volatility. The bank should develop premium domiciliary products — offering competitive FX rates, international wire transfers, and dollar-denominated investment options to retain these customers
- The heavy skew toward the ₦500M+ balance tier means the bank's revenue is concentrated in a small wealthy segment, creating dependency risk. A financial inclusion strategy targeting the <₦100K and ₦100K–₦500K tiers — through low-minimum savings products and micro-investment accounts — would diversify the balance sheet
- Top account officers like Paul Holmes and Jonathan Hawkins are managing significantly higher average balances than peers. The bank should document and replicate their relationship management practices across the wider team through structured training
- The uptick in account openings post-2000 reflects growth momentum. The bank should analyse what drove that growth and replicate those conditions — whether it was branch expansion, product launches, or marketing — to sustain new account acquisition going forward


## 🗂️ Dataset Structure

| Sheet | Records | Description |
|---|---|---|
| `Customer` | 3,011 rows | Customer demographics, deposits, savings |
| `Accounts` | 3,000 rows | Account type, opening balance, account officer |
| `Loan` | 300 rows | Loan amounts per customer |
| `Transaction` | 3,000 rows | Transaction type, medium, amount, date |
| `Transaction time` | 3,000 rows | Time of day for each transaction |

**Key Fields:** `Customer_id`, `Age`, `Sex`, `Occupation`, `City`, `Bank Deposit`, `Saving Accounts`, `Account Type`, `Opening Balance`, `Bank Loans`, `Transaction type`, `Transaction Medium`, `Amount`



## 🛠️ Tools & Skills Used

| Tool | Usage |
|---|---|
| **Power BI Desktop** | Dashboard design, DAX measures, data modelling |
| **Microsoft Excel** | Raw data source (5 relational sheets) |
| **DAX** | KPI calculations, ratio metrics, conditional aggregations |
| **Power Query** | Data cleaning, type casting, relationship building |



## 💡 Key Business Questions Answered

- Which cities and occupations drive the most banking value?
- What is the bank's loan penetration rate and which demographics borrow most?
- How are transactions distributed across channels and time periods?
- Which account types hold the most wealth, and how are balances distributed?
- Which account officers manage the highest-value customer portfolios?



## 📁 Repository Structure

```
banking-analytics-dashboard/
│
├── README.md                        # This file
├── Bank customer details 1.xlsx    # Source dataset
├── Banking Data Story Telling project 2.pbix           # Power BI dashboard file
└── screenshots/
    ├── 01_customer_profile.png
    ├── 02_loan_analytics.png
    ├── 03_transaction_trends.png
    └── 04_account_balance.png




## 📸 Dashboard Preview

| Page | Preview |
|---|---|
| Customer Profile Summary | ![Customer Profile](screenshots/01_customer_profile.png) |
| Loan Analytics | ![Loan Analytics](screenshots/02_loan_analytics.png) |
| Transaction Trends | ![Transaction Trends](screenshots/03_transaction_trends.png) |
| Account Balance Distribution | ![Account Balance](screenshots/04_account_balance.png) |



## 👤 Author

FALADE FAVOUR TOLUWANIMI  
Data Analyst | Power BI Developer  
📧 favourfalade0311@gmail.com 
🔗 [LinkedIn Profile](https://www.linkedin.com/in/favour-falade )  
🐙 [GitHub](https://github.com/Favour311)



*This project was built as part of a data analytics portfolio to demonstrate proficiency in Power BI, DAX, data modelling, and financial data storytelling.*
