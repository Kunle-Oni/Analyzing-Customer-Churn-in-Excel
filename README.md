# Customer Churn Analysis – Databel Telecom (Excel)

## 🔍 Project Overview
This project analyzes customer churn for **Databel**, a fictitious telecommunications provider, using **Microsoft Excel**.  
The objective is to identify **why customers are leaving**, uncover the **key drivers of churn**, and provide **data-driven recommendations** to improve customer retention. The analysis follows a structured data analytics workflow, combining data cleaning, exploratory analysis, visualization and insight communication.

---

## Business Problem
Databel is experiencing a **high customer churn rate**. Management wants to understand:
- The **overall churn level**
- The **primary reasons customers leave**
- Which **customer segments are most at risk**
- Whether Databel is **competitive** in pricing, devices, and service offerings

<img width="657" height="71" alt="Screenshot 2026-01-16 at 21 50 46" src="https://github.com/user-attachments/assets/e16d6d65-a7a8-4de4-8344-eb15f98752f8" />

---

## Data Analysis Workflow (Excel)

1. **Data Quality Check**
   - Identified and removed duplicate records using **Conditional Formatting**
2. **Data Exploration**
   - Reviewed customer attributes and churn indicators
3. **Analysis & Visualization**
   - Pivot Tables, formulas, and charts used to uncover churn drivers
4. **Dashboarding**
   - Summary visuals to highlight key patterns
5. **Insight Communication**
   - Business-focused insights and recommendations

---

## Key Metrics & Overall Churn

- **Total churn rate:** **26.86%**
- **Customers churned:** Over **1,750 customers**
- Pivot tables were used to:
  - Count total customers
  - Count churned customers
  - Calculate churn rate

This churn level indicates a **significant retention challenge** requiring immediate action.

<img width="657" height="71" alt="Screenshot 2026-01-16 at 21 50 46" src="https://github.com/user-attachments/assets/edf972a5-8ad1-4b3a-b5c9-9de7a48efca6" />

---

## Primary Drivers of Churn

Analysis of churn reasons revealed the **top three drivers**:

1. **Attitude of support personnel**
2. **Competitors offering better devices**
3. **Competitors offering better pricing**

These findings highlight both **service quality** and **competitive pressure** as major contributors to churn.

<img width="660" height="278" alt="Screenshot 2026-01-16 at 21 47 39" src="https://github.com/user-attachments/assets/7411fc74-bb89-4f41-a9fe-5be73828e1a7" />

---

## Churn Category Analysis (Priority Assessment)

Churn reasons were grouped into broader categories to identify where Databel is losing the most customers.

- The **Competitor category** accounts for the **highest proportion of churn**
- A pie chart was used to break down this category further:
  - **Competitor made better offer** (largest driver)
  - **Competitor had better devices** (second largest)

🔎 **Key Question Raised:**  
Is Databel sufficiently competitive in pricing and device offerings?

<img width="659" height="298" alt="Screenshot 2026-01-16 at 21 47 29" src="https://github.com/user-attachments/assets/c97ba6c4-b556-4894-ab07-3ef1e539f22b" />

---

## Demographic Analysis – Age & Churn

### Age Grouping
- Customers were categorized using the `IF()` function
- Churn rate was calculated by age demographic

### Key Findings
- **Senior citizens** show the **highest churn rate**
- Customers **under 30** show the **lowest churn rate**

Further age segmentation using **age bins** revealed:
- The **79–88 age group** has:
  - The **highest churn rate**
  - The **smallest customer base**
- A **combo chart** was used to show:
  - Number of customers per age bracket
  - Corresponding churn rate

<img width="377" height="224" alt="Screenshot 2026-01-16 at 21 46 53" src="https://github.com/user-attachments/assets/acec4108-a0f6-43ba-93ad-f44040036e6e" />

---

## Plan Type Analysis – Unlimited Data

- Customers on **unlimited data plans** are **more likely to churn**
- Further investigation showed:
  - Unlimited plan users consuming **less than 5GB/month** have a **34.69% churn rate**

🔎 This suggests a **value mismatch** between pricing and actual usage.

<img width="372" height="204" alt="Screenshot 2026-01-16 at 21 47 06" src="https://github.com/user-attachments/assets/dc12596d-cf76-43d6-a805-47191c9f8207" />

---

## International Plan & Geographic Insights

- Churn behavior was analyzed for customers with **international calling plans**
- **California (CA)** stands out with:
  - A particularly **high churn rate** among international plan users

This may indicate **pricing, coverage, or customer expectation gaps** in that region.

<img width="264" height="586" alt="Screenshot 2026-01-16 at 21 56 52" src="https://github.com/user-attachments/assets/155022c8-4887-4874-8895-73764f8c9cb1" />

---

## Contract Type & Customer Loyalty

- Churn rates decrease as **contract length increases**
- **Month-to-month contracts** show the **highest churn**
- Longer-term contracts demonstrate:
  - Greater customer stability
  - Lower churn rates

---

## Key Insights Summary

- Databel’s churn is driven primarily by **competitive pressure** and **service experience**
- **Senior customers** and **month-to-month users** are the most vulnerable segments
- Unlimited plans may not be aligned with actual customer usage
- Regional churn patterns suggest localized issues

<img width="1358" height="659" alt="Screenshot 2026-01-16 at 21 46 16" src="https://github.com/user-attachments/assets/fd36521c-1a88-43a4-9418-821c0363b31d" />

---

## Recommendations for Databel

### 1️⃣ Improve Competitive Positioning
- Review pricing strategy to match or beat competitor offers
- Enhance device portfolio, especially in high-churn segments

### 2️⃣ Enhance Customer Support Quality
- Invest in support staff training
- Monitor service interactions for senior customers

### 3️⃣ Revisit Unlimited Data Plans
- Introduce **tiered or flexible plans** for low-data users
- Align pricing with actual consumption patterns

### 4️⃣ Target High-Risk Segments
- Develop retention campaigns for:
  - Senior citizens
  - Month-to-month contract customers
- Offer incentives for contract upgrades

### 5️⃣ Regional Strategy Optimization
- Investigate churn drivers in **California**
- Customize international plan offerings by region
