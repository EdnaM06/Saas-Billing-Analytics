# 💳 SaaS Billing & Revenue Analytics

## 🧠 Project Overview

This project analyzes subscription billing data for a SaaS product to evaluate revenue performance, customer retention, and monetization efficiency.

The analysis simulates a real-world **Billing / Revenue Analyst role**, focusing on identifying revenue leakage, churn drivers, and growth opportunities.

> How can we reduce churn, improve revenue stability, and optimize subscription performance?

---

## 🏢 Business Context

Subscription-based companies depend on:
- Stable Monthly Recurring Revenue (MRR)
- Low churn rates
- Strong user engagement

However, common challenges include:
- High customer churn reducing revenue predictability  
- Poor conversion from free to paid plans  
- Revenue concentration across limited markets  
- Weak onboarding leading to early user drop-off  

This project focuses on identifying these issues and providing actionable solutions.

---

## 📊 Dataset

**Source:** SaaS Product Dashboard Dataset (Kaggle)  
**Author:** Philbert Chan  
**License:** CC0 Public Domain  

### Includes:
- User subscription records  
- Subscription plans (Free, Basic, Pro)  
- Event logs (user engagement)  
- Country-level data  
- Revenue transactions  

---

## 🛠 Tools & Technologies

- SQL (MySQL)
- CTEs & Views
- Data Cleaning & Transformation
- Git & GitHub
- *(Planned)* Mixpanel (event analytics)
- *(Planned)* Power BI (dashboarding)

---

## 📊 Key Metrics Analyzed

| KPI | Description |
|-----|------------|
| MRR | Monthly Recurring Revenue trends |
| Churn Rate | Cancelled users ÷ active users |
| ARPU | Average Revenue Per User |
| MAU | Monthly Active Users |
| Plan Distribution | Revenue and user breakdown by plan |
| Country Revenue | Revenue contribution by region |

---

## 📈 Key Findings

### 1. Revenue & MRR Trends
- MRR peaked in February 2022 ($520)
- Significant decline observed in April due to reduced active users
- Revenue is highly dependent on user activity levels

---

### 2. Churn Analysis
- Churn reached **26% in June**
- Far above SaaS benchmarks (~5–7%)
- Indicates major retention issues, especially early in the user lifecycle

---

### 3. Plan Performance
- Free plan dominates user acquisition
- Pro plan generates highest ARPU
- Low conversion from Free → Pro suggests monetization gap

---

### 4. Geographic Revenue Distribution
- Canada contributes ~37.6% of total revenue
- Revenue heavily concentrated in one region
- Indicates geographic risk and lack of diversification

---

### 5. Engagement & Revenue Relationship
- High MAU correlates strongly with higher MRR
- Decline in engagement leads directly to revenue drop
- Engagement is a leading indicator of revenue performance

---

## 💡 Business Recommendations

### 1. Reduce Early Churn
- Implement onboarding flows targeting first 30–90 days  
- Introduce engagement triggers (email, in-app prompts)  

---

### 2. Improve Monetization Strategy
- Optimize Free → Pro conversion with targeted upgrade campaigns  
- Introduce feature gating for premium value  

---

### 3. Stabilize Revenue Growth
- Focus on increasing MAU through retention strategies  
- Replicate high-performing acquisition periods  

---

### 4. Reduce Geographic Risk
- Expand acquisition in underperforming regions  
- Tailor pricing or campaigns by market  

---

## 🚀 Expected Business Impact

If implemented:
- Reduced churn rate → more stable MRR  
- Increased ARPU through better plan conversion  
- Improved customer lifetime value (LTV)  
- More predictable revenue growth  

---

## 🧠 Skills Demonstrated

- Subscription revenue analysis (MRR, ARPU, churn)
- Cohort-style churn analysis
- Business KPI interpretation
- SQL data modeling using CTEs and views
- Translating data into actionable business decisions

---

## 📂 Project Status

🚧 In Progress:
- Adding Mixpanel-style event analysis  
- Building Power BI dashboard  
- Extending cohort and retention analysis  

---

## 👤 Author

Data Analytics Portfolio Project  
Focused on SaaS Analytics, Revenue Optimization, and Growth Strategy
