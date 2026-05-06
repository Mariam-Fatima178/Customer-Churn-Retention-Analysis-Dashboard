# 📉 Customer Churn & Retention Analysis Dashboard

## Project Overview

This project analyzes customer churn patterns and service-related churn drivers in a telecom dataset using **Power BI**. The goal is to support data-driven retention strategies by identifying high-risk customer segments and the key factors contributing to churn.

The dataset covers **7,043 total customers** with an overall churn rate of **26.54%**. Despite paying higher average monthly charges ($74.4), churned customers generate significantly lower lifetime value ($1,531) compared to retained customers ($2,549) — proving that price alone cannot sustain loyalty.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Dashboard design and interactive reporting
- **DAX** — Calculated measures and churn rate logic
- **Power Query** — Data cleaning and transformation
- **Drill-Through Analysis** — Cross-page root cause investigation

---

## 📊 Dashboard Structure

### 1️⃣ Customer Churn Overview Page
Identifies where churn is highest and lowest by analyzing:
- Churn distribution across **tenure groups** and **monthly charge ranges**
- Side-by-side comparison of churned vs retained customer volumes

### 2️⃣ Drill-Through Page — Churn Drivers
Uncovers the underlying causes of churn by breaking down customers across:
- Contract type, Payment method, Tech support availability, Internet service type

---

## 🔍 Key Insights

- **Tenure** — Churn is highest in the 0-1 year group and drops consistently as tenure grows. Surviving the first year is the most critical retention milestone.
- **Monthly Charges** — The $60–$90 range is the peak churn danger zone. Customers pay enough to feel pressure but lack the commitment or support to justify the cost.
- **Contract Type** — 88.55% of all churned customers were on month-to-month contracts vs 57% of retained customers on annual or two-year plans. The single strongest churn predictor.
- **Tech Support** — 77% of churned customers had no tech support. Retained customers show significantly higher adoption — unresolved problems silently drive churn.
- **Fiber Optic** — Carries an alarming 41.89% overall churn rate vs DSL at 18.96%, indicating a product-level issue beyond just customer behavior.
- **Payment Method** — Electronic check dominates the churned segment while auto-pay customers are consistently overrepresented in the retained segment, reflecting stronger commitment.

---

## 💡 Business Recommendations

1. **Incentivize annual contracts within the first 90 days** to convert high-risk month-to-month customers before churn behavior forms.
2. **Bundle tech support into new customer plans** proactively rather than offering it as an optional add-on.
3. **Review Fiber Optic service quality and pricing** — a behavioral fix alone will not resolve a product-level problem with a 41.89% churn rate.
4. **Promote auto-pay enrollment** through discounts or rewards to reduce electronic check dependency and strengthen commitment signals.

---

## 📌 Conclusion

Every churn driver identified — contract type, tenure, tech support, fiber optic risk, and payment behavior — points to the same window of opportunity: **the first 90 days of a customer's tenure**. Early intervention during this period has the highest potential to permanently shift a customer from high-risk to long-term loyal.
