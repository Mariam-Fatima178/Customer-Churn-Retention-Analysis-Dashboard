# Customer Churn & Retention Analysis Dashboard
## Project Overview
This project analyzes **customer churn patterns** and **key service-related churn drivers** in a telecom dataset using **Power BI**.  
The main objective is to support **data-driven retention strategies** by identifying high-risk customer segments and understanding the service-level factors that contribute to churn.

The analysis is structured using:
- A **Churn Overview** page to identify where churn is highest and lowest
- A **Drill-Through** page to investigate the underlying causes of churn by comparing churned and non-churned customers

## Tools & Technologies
- Power BI Desktop  
- DAX
- Data Cleaning & Transformation  
- Interactive Dashboards & Drill-Through Analysis  

## Analysis Focus
- Identify churn patterns based on **tenure** and **monthly charges**
- Detect **high-churn and low-churn customer segments**
- Drill down into **service usage** to uncover churn drivers
- Compare **churned vs non-churned customers** to explain churn behavior

## 📊 Dashboard Structure

### 1️⃣ Customer Churn Overview Page
Provides a high-level view of what is driving churn by focusing on:
- Churn distribution by **tenure groups**
- Churn distribution by **monthly charge ranges**
- Identification of tenure and pricing segments with:
  - Highest churn
  - Lowest churn
This page answers:
> *At which tenure lengths and monthly charge ranges is churn most prevalent?*

### 2️⃣ Drill-Through Page – Churn Drivers
The drill-through page is used to identify the **underlying service-related causes** of churn.
From the overview page, users can drill through any:
- Tenure group  
- Monthly charge range  

To analyze customer distribution by:
- Contract type  
- Payment method  
- Tech support availability  
- Internet service usage  

## 🔍 Key Insights
- Churn is highest among customers with:
  - Month-to-month contracts
  - Electronic check payment method
  - No tech support
  - Fiber optic internet service
- Customers with longer tenure show lower churn rates
- Retained customers display a more balanced service distribution compared to churned customers

## Business Recommendations
1. Bundle **tech support** with month-to-month plans to reduce churn among high-risk customers  
2. Offer **targeted discounts** for customers with high monthly churn risk  
3. Promote **auto-pay payment methods** over electronic check to improve retention

## How to Use
1. Open the `.pbix` file in **Power BI Desktop**
2. Explore the **Churn Overview** page
3. Use **drill-through** on tenure or monthly charge visuals
4. Compare churned vs non-churned customers to identify churn drivers
