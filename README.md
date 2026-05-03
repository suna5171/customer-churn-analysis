# Customer Churn Analysis & Risk Segmentation Dashboard

Telecom customer churn analysis using Python and Power BI — identifying 1,703 high-risk customers and key churn drivers to support retention strategies.

## Business Problem

A telecom company was losing **27% of its customers** with no visibility into who was at risk or why they were leaving.

**Goal:** Analyse churn behaviour → segment high-risk customers → recommend retention strategies

## Key Numbers

| Metric | Value |
|--------|-------|
| Total customers analysed | 7,032 |
| Total churned | 1,869 |
| Overall churn rate | 27% |
| Month-to-month churn rate | 43% |
| Two-year plan churn rate | 3% |
| Churn risk difference | ~14x higher for monthly contracts |
| Fiber optic churn rate | 42% |
| No tech support churn rate | 42% |
| High-risk customers flagged | **1,703** |
| High Risk segment | 43.91% |
| Medium Risk segment | 42.7% |
| Low Risk segment | 13.39% |

---

## Tools Used

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning, EDA, risk segmentation |
| Power BI + DAX | Interactive 2-page dashboard |

---

## What I Did

**1. Data Cleaning (Python)**
- Analysed 7,032 customer records
- Fixed TotalCharges column (blank values for new customers, filled with median)
- Encoded categorical columns for analysis
- Focused on translating data into business insights rather than only technical analysis

**2. Key Findings**
- Month-to-month customers churn ~14x more than two-year plan holders
- Fiber optic and no-tech-support customers both hit 42% churn
- New customers (low tenure) are most at risk — churn drops significantly after month 20

**3. Risk Segmentation**
- Created a rule-based churn risk segmentation using customer behaviour patterns
- Segmented customers into Low / Medium / High risk categories
- Flagged 1,703 high-risk customers for targeted retention outreach

**4. Power BI Dashboard**
- Page 1: Churn analysis by contract type, internet service, tech support, tenure
- Page 2: Risk segments, high-risk customers by monthly charges and contract type
- DAX measures for dynamic KPIs across all slicers (Gender, PaymentMethod, CustomerType)

---

## Recommendations

1. Target the **1,703 high-risk customers** with immediate retention campaigns
2. Offer incentives to move monthly users onto annual plans
3. Improve fiber optic service quality — 42% churn signals pricing or reliability issues
4. Strengthen onboarding for new customers in the first 20 months
5. Bundle tech support with new contracts — drops churn from 42% to 15%

---

## Dataset

- Source: IBM Telco Customer Churn Dataset (publicly available)
- Size: 7,032 records, 21 features
- Domain: Telecom / Customer Retention

---

## About Me

**Sunama Jena** | Data Analyst | MCA, NIST University (CGPA 8.4) | Immediate Joiner

📧 jenasunama5@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/your-linkedin-url)
📁 [More Projects](https://github.com/suna5171)
