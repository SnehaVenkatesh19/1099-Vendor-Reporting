# 1099 Vendor Reporting & Payment Analysis

This project simulates a real-world financial and compliance scenario involving vendor payments over a production cycle. Using synthetic data and SQL-based logic, it identifies vendors eligible for IRS 1099 reporting, tracks payment trends, and visualizes key insights with Tableau.

## Objective

To build a data pipeline and dashboard that mirrors how production finance teams might:
- Track monthly spend  
- Identify high-value vendors  
- Flag IRS 1099 eligibility  
- Surface insights for audits and compliance

---

## Tableau Dashboard

 [View Interactive Dashboard on Tableau Public](https://public.tableau.com/app/profile/sneha.venkatesh3644/viz/1099ReportingforVendors/Dashboard1)

---

## Key Findings

### 1. Monthly Expense Trend
- Payment volumes varied across the year.
- Noticeable **spikes** in June and October suggest high-production activity (e.g., filming wrap-up or bulk vendor payouts).
- These trends can guide budgeting cycles and production planning.

### 2. High-Value Vendor Analysis
- Vendors like **Ferrell, Rice and Maddox** and **Ross, Robinson and Bright** received significantly higher payouts.
- These may be repeat service providers or high-risk from an audit perspective.
- Important to monitor closely for contract, renewal, or tax reporting obligations.

### 3. Average Payment per Vendor
- Some vendors received large one-time payments; others were paid smaller amounts consistently.
- Helps differentiate between **contracted professionals** and **ad-hoc service vendors**.

### 4. 1099 Reporting Status Breakdown
- Most vendors surpassed the $600 IRS threshold and were marked **“Eligible.”**
- A few low-paid vendors were simulated as **“Not Eligible”** for illustrative purposes.
- Bar chart with **dual axis** (count vs total paid) clearly shows disproportionate payment concentration in eligible vendors.

---

## Tools Used

| Tool      | Purpose                         |
|-----------|---------------------------------|
| Python    | Data generation, ETL, validation |
| MySQL     | Data storage, query logic       |
| AWS RDS   | Cloud-based database hosting    |
| Tableau   | Dashboard and storytelling      |
| Colab     | Pipeline testing and scripting  |



