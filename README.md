# Moniepoint Merchant Value & Risk Intelligence Dashboard

## Identifying Merchant Retention Opportunities and Financial Risk Through Data-Driven Portfolio Analysis

## Project Overview

This project analyzes a simulated portfolio of **10,000 merchants** to understand merchant value, transaction activity, churn, credit exposure, repayment risk, and fraud-related indicators.
<img width="837" height="599" alt="Screenshot 2026-11-21 051453" src="https://github.com/user-attachments/assets/7b24d01c-90ea-4658-bdae-7d515ac0794e" />

The dashboard was designed from a **Business Analyst and portfolio-risk perspective**, focusing on the business questions behind the data rather than simply presenting charts.

The central question is:

> **Which merchants are most valuable, which are most likely to churn, and where is the business most exposed to financial and operational risk?**

---

## Business Problem

A large merchant portfolio can generate significant transaction volume and revenue while simultaneously carrying risks such as:

- Merchant churn
- Declining transaction activity
- Credit exposure
- Loan delinquency and default
- Fraud alerts
- Chargebacks
- Concentrated geographic risk

Looking at these indicators separately can make it difficult to identify where management should intervene.

This project brings these dimensions together into a single decision-support dashboard.

---

## Analytical Framework

The analysis follows this business storyline:

**Merchant Activity → Merchant Value → Engagement → Churn Risk → Credit Risk → Fraud Risk → Financial Exposure → Business Action**

The objective is to move from:

**“What happened?”**

to:

**“Where is the risk?”**

and ultimately:

**“What should the business do?”**

---

## Key Portfolio Metrics

The dashboard provides visibility into:

- Total merchants
- Active merchants
- Churned merchants
- Churn rate
- At-risk merchants
- Transaction value
- Estimated monthly revenue
- Total loan exposure
- Outstanding loan balance
- Default rate
- Expected credit loss
- Fraud alerts
- Chargebacks
<img width="664" height="156" alt="image" src="https://github.com/user-attachments/assets/12a1f371-3de9-4776-b787-065db5036c9c" />

---

## Dashboard Analysis

### Portfolio Health

The executive overview provides a high-level assessment of the merchant portfolio.

It answers:

- How large is the merchant portfolio?
- How many merchants remain active?
- How many merchants have churned?
- What percentage of merchants are at risk?
- How much transaction value is being generated?
- How much credit exposure exists?

This gives management an immediate view of overall portfolio health.

---

### Merchant Value

Merchants are segmented into:

- High Value
- Medium Value
- Low Value

Merchant value is based on estimated monthly revenue.

The analysis helps identify whether potential churn is concentrated among high-value merchants.

A key finding from the dashboard is that **120 of the 149 at-risk merchants are classified as High Value**, making high-value merchant retention an important business priority.
<img width="276" height="118" alt="image" src="https://github.com/user-attachments/assets/aef7d3d1-7327-477d-81f7-4a406d02af4f" />

---

### Transaction Performance

Monthly transaction values are analyzed from **May 2026 through October 2026**.

The transaction trend helps identify changes in portfolio activity and creates opportunities for further investigation into:

- State-level growth
- Business-type performance
- Merchant contribution
- Transaction volume
- Average transaction value

A significant movement in transaction value can be investigated to understand which merchants or segments are responsible for the change.

---

### Merchant Churn

Churn is analyzed using merchant churn dates.

The dashboard helps identify:

- Churn volume over time
- Churn rate
- At-risk merchants
- High-value merchants at risk
- Churn concentration across the portfolio
<img width="396" height="113" alt="image" src="https://github.com/user-attachments/assets/24bdb632-5dac-4d7d-82d0-f34356fc589f" />

The objective is not only to measure churn but to identify merchants who may require retention intervention.

---

### Credit Risk

The credit-risk analysis evaluates:

- Total borrowers
- Loan amount
- Outstanding balance
- Credit-risk bands
- Expected credit loss

This helps answer:

> **Where is the business carrying the greatest credit exposure?**

---

### 6. Expected Credit Loss

Expected Credit Loss (ECL) is used as a portfolio-risk indicator.

For this project, ECL is simulated using:

**ECL = Outstanding Balance × Probability of Default × Loss Given Default**

The metric estimates the amount of current outstanding exposure that could potentially become a loss.


---

### Geographic Analysis

Merchant activity is analyzed across Nigerian states and regions.

The geographic view helps identify:

- Merchant concentration
- Transaction-value concentration

filter dashboard by state, region, city tier, business type, and other dimensions to investigate specific markets.

---

## Key Business Questions

The dashboard was designed to answer questions such as:

1. Which merchants generate the greatest economic value?
2. How many merchants are currently at risk?
3. Are high-value merchants disproportionately represented among at-risk merchants?
4. Where is transaction value concentrated?
5. Which credit-risk bands carry the largest outstanding exposure?
6. Where is expected credit loss concentrated?
7. Which states have the highest portfolio risk?
8. How are fraud alerts and chargebacks distributed?
9. Is credit risk associated with merchant churn?
10. Which merchants should receive retention, credit, fraud, or growth interventions?

---

## Recommended Business Actions

The analysis supports several potential actions:

### Retention Intervention
Prioritize high-value merchants showing elevated churn risk.

### Credit Review
Review merchants with significant outstanding balances and elevated credit risk.

### Fraud Investigation
Investigate merchants with critical fraud indicators or unusual transaction behaviour.

### Product Cross-Sell
Identify valuable merchants using relatively few products and evaluate relevant product-adoption opportunities.

### Growth Opportunity
Prioritize high-value merchants with strong engagement, low churn risk, and low credit risk for growth initiatives.

### Standard Monitoring
Continue monitoring merchants without significant risk indicators.

---

## Tools & Technologies

- Power BI
- DAX
- Excel
- Data visualization
- Business analysis
- Portfolio risk analysis

---

## Key Insight

The most important analytical principle behind the project is that **merchant risk should not be viewed from one dimension alone**.

A merchant may be:

- Highly valuable but likely to churn
- Low churn risk but highly exposed to credit risk
- High transaction value but showing fraud indicators
- Low credit risk but underusing available products

Therefore, combining **merchant value + engagement + churn + credit + fraud** creates a more useful decision framework than analyzing any single metric independently.

---

## Conclusion

This project demonstrates how transactional, behavioural, financial, and risk indicators can be transformed into a business-oriented decision-support system.

<img width="837" height="599" alt="Screenshot 2026-11-21 051453" src="https://github.com/user-attachments/assets/16964578-db7a-44e8-bf9c-855f57b0b38d" />


> **Where should management focus attention, which merchants require intervention, and where is the greatest financial opportunity or risk?**

That is the core of the **Moniepoint Merchant Value & Risk Intelligence Dashboard**.
