# 📊 SaaS Billing & Revenue Analytics (SQL Project)

## 🎯 Project Overview

This project analyzes subscription billing data from **January 2022 to June 2022** for a SaaS product to evaluate revenue performance, customer retention, and monetization efficiency.

The goal was to simulate a real-world Billing / Revenue Analyst role by analyzing:

- Monthly Recurring Revenue (MRR)
- Churn Rate
- Average Revenue Per User (ARPU)
- Subscription Plan Performance
- Revenue Distribution by Country
- Engagement-to-Revenue Correlation

---

## 📁 Dataset

**Source:** SaaS Product Dashboard Dataset – Kaggle  
**Author:** Philbert Chan  
**License:** CC0 1.0 Public Domain  

The dataset includes:
- User subscription records
- Plan information (Free, Basic, Pro)
- Event logs
- Country distribution
- Revenue data

### Data Preparation
Data cleaning included:
- Handling null subscription and cancellation dates
- Removing duplicate user IDs
- Standardizing date formats for monthly aggregation
- Validating revenue fields for numeric consistency

---

## 🛠 Tools & Technologies

- SQL (MySQL)
- CTEs & Views
- Data Cleaning & Transformation
- Git & GitHub

---

## 📊 Key KPIs Analyzed

| KPI | Description |
|------|------------|
| MRR | Monthly Recurring Revenue trend |
| Churn Rate | Monthly customer attrition rate (Cancelled Users ÷ Active Users at Start of Month) |
| ARPU | Average Revenue Per User |
| Plan Distribution | User and revenue share by subscription plan |
| Country Revenue | Revenue contribution by country |
| MAU | Monthly Active Users |

---

## 📈 Key Findings

### 1️⃣ Revenue & MRR Trends
- MRR peaked in **February 2022 ($520)**
- MRR dropped significantly in April due to declining active users
- Revenue showed strong correlation with active user levels

### 2️⃣ Churn Analysis
- Monthly churn reached **26% (June 2022)**
- This exceeds typical SaaS industry benchmarks (~5–7%)
- High churn indicates need for structured early-stage retention strategy

### 3️⃣ Plan Performance
- Free plan has highest signup volume
- Pro plan generates highest ARPU
- Opportunity exists to improve Pro plan adoption through upgrade incentives

### 4️⃣ Geographic Revenue
- Canada contributes **37.58% of total revenue**
- India shows lowest contribution
- Revenue concentration risk identified due to geographic dependency

### 5️⃣ Engagement & Revenue Correlation
- Stable MAU in early months aligned with higher MRR
- Decline in MAU directly correlated with revenue drop

---

## 💡 Business Recommendations

- Introduce targeted upgrade campaigns to increase Pro plan conversion
- Implement structured onboarding engagement campaigns to reduce churn within first 90 days
- Replicate successful January acquisition strategies
- Develop engagement initiatives to stabilize and grow MAU

---

## 🧠 Skills Demonstrated

- Subscription revenue modeling
- Churn rate calculation using cohort-based logic
- ARPU and MRR computation
- Business KPI reporting
- SQL data transformation using views and CTEs
- Executive-level insight communication

---

## 📂 Project Structure
