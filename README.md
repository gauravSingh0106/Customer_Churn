# Customer Churn Analysis Dashboard

An interactive Power BI dashboard analyzing customer retention patterns across 50,000 customers, built to identify high-risk segments and uncover the operational and demographic drivers of churn.

## 📊 Overview

Customer churn directly impacts recurring revenue, and spotting it early is far cheaper than winning customers back. This project digs into a 50,000-customer dataset to understand **who is churning, why, and where the business should focus retention efforts**.

The dashboard tracks churn metrics in real time and breaks them down by age, contract type, payment method, and monthly charges — giving stakeholders a clear view of customer loyalty health at a glance.

## 🔗 Resources

- **Dataset:** [customer_churn_dataset_50000.csv](https://github.com/gauravSingh0106/Customer_Churn/blob/main/customer_churn_dataset_50000.csv)
- **Dashboard Screenshot:** [View here](https://github.com/gauravSingh0106/Customer_Churn/blob/main/custoemr%20chhurn.png)

## ❓ Business Questions Addressed

- What is the overall customer churn rate?
- How many active customers do we currently have?
- Which demographic groups (age and gender) show the highest tendency to churn?
- How do operational factors — contract type and payment method — correlate with customer loss?
- Are customers with higher monthly charges more likely to leave?
- What specific segments represent the highest risk to the business?

## 📈 Key Performance Indicators (KPIs)

| Metric | Value |
|---|---|
| Total Customers | 50,000 |
| Active Customers | 39,000 |
| Churned Customers | 11,000 |
| Churn Rate | 22% |

## 🔍 Key Insights & Findings

- **Demographic Triggers:** Senior citizens are the most vulnerable segment, accounting for the highest volume of churned customers (**5,681**) compared to middle-aged and younger cohorts.
- **Risk Breakdown:** Of the 11,002 total churned customers, a striking **10,179** fell into the "Low Risk" behavioral category before leaving — churn is happening quietly, without traditional high-risk warning signs, pointing to a need for deeper engagement metrics.
- **Contract & Operational Impact:** **Monthly contracts** are the single biggest driver of churn, accounting for **7,837** lost customers versus yearly or quarterly commitments.
- **Financial Thresholds:** Customers on lower monthly charges (<80) make up the largest share of churn (36%), closely followed by mid-tier spenders (80–120) at 33%.
- **Tenure Vulnerability:** Churn peaks among long-term customers with tenure **>40 months** (4,379 customers), suggesting a loyalty drop-off or uncompetitive long-term pricing.

## 🛠️ Tools Used

- **Power BI** — dashboard design & DAX calculations
- **Excel** — data cleaning & preprocessing

## 💡 Recommendations

- Introduce loyalty incentives targeted at long-tenure customers (>40 months) to counter the late-stage drop-off.
- Promote annual/quarterly plans over monthly contracts through pricing incentives, given their outsized churn contribution.
- Build proactive engagement triggers for "Low Risk" customers, since most churn originates here rather than from flagged high-risk accounts.
- Review pricing tiers for the <80 monthly charge segment to understand what's pushing budget-conscious customers out.


