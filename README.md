# Customer Churn Analysis & Prediction

## Overview

In this project, I worked on analyzing customer churn for a telecom company and built a model to predict which customers are likely to leave. The idea was not just to find patterns, but also to turn those insights into something useful for business decisions.

---

## Business Problem

The company is losing a significant number of customers (~27%), but they don’t clearly understand:

* who is likely to churn
* and what factors are causing it

So the goal was simple:
👉 understand churn behavior
👉 predict high-risk customers
👉 suggest ways to reduce churn

---

## Tools Used

* **Python** for data cleaning and building the prediction model
* **Power BI** for creating dashboards and insights

---

## What I Did in Python

* Cleaned and prepared the dataset
* Converted categorical data into usable format
* Built a churn prediction model
* Generated:

  * Churn Prediction (0 or 1)
  * Churn Probability (risk score)

These outputs were later used in Power BI to identify high-risk customers.

---

## Dashboard Explanation

### Page 1 – Churn Analysis (Understanding the Problem)

This page focuses on *why customers churn*.

**KPIs:**

* Total Customers: 7032
* Total Churn: 1869
* Churn Rate: 27%
* Avg Monthly Charges: 64.80

**Insights from charts:**

* Month-to-month customers churn the most
* Customers with low tenure are more likely to leave
* Fiber internet users show higher churn
* Customers without tech support have higher churn

---

### Page 2 – Prediction & Risk (Solving the Problem)

This page focuses on *who is likely to churn*.

**KPIs:**

* High Risk Customers: 571
* Predicted Churn: 2076
* Predicted Churn Rate: 0.42

**What this shows:**

* Most high-risk customers are on month-to-month contracts
* Higher monthly charges are linked with higher risk
* Customers are grouped into Low, Medium, and High risk

---

## Key Learnings / Insights

* Contract type is a major factor in churn
* New customers are more vulnerable
* Pricing and support quality directly impact retention
* Prediction models help prioritize which customers to target

---

## Business Recommendations

* Focus retention efforts on high-risk customers
* Encourage users to move to long-term contracts
* Offer discounts or benefits to valuable customers
* Improve customer support experience
* Pay extra attention to new customers early

---

## Conclusion

This project helped me understand how data analysis and prediction can work together. Instead of just looking at past churn, I was able to identify future risk and suggest actions.

It shows how businesses can move from **reactive decisions to proactive strategies** using data.
