# Customer Retention & Churn Analysis

## Project Overview
This project is part of my **Data Science & Analytics Internship** at **Future Interns**. The goal was to analyze subscription data for a California-based telecommunications company to identify the key drivers of customer churn, quantify revenue impact, and develop targeted retention strategies.

## Key Insights
* **Churn Rate:** Over 1 in 4 customers (26.5%) churned within the last month which far exceeds healthy industry benchmarks and signalling an urgent retention problem.
* **Contract Risk:** Month-to-month subscribers are the highest-risk segment, with churn rates significantly higher than customers on annual or two-year plans (χ² p < 0.0001).
* **Critical Window:** Churn is most likely within the first 12 months of a subscription, making early engagement the single most important retention lever.
* **Pricing Pressure:** Churned customers pay higher monthly charges on average (ANOVA p < 0.0001), with Fiber Optic users (the premium tier) churning at disproportionately high rates.
* **Bundling Works:** Customers subscribed to multiple add-on services (Tech Support, Online Security) churn at significantly lower rates, confirming that bundling raises switching costs.
* **Revenue at Risk:** The business faces ~$139,131 in monthly revenue leakage and over $2.86 million in cumulative lifetime value lost to churn.

## Recommendations
* **Incentivise annual contracts** for month-to-month subscribers through discounts or service upgrades to lock in retention early.
* **Implement a 90-day onboarding programme** with structured check-ins to reduce first-year churn during the critical vulnerability window.
* **Bundle Tech Support and Online Security** into at-risk plans via free trials to increase switching costs and perceived value.
* **Audit Fiber Optic pricing** and consider price-lock guarantees to address the gap between premium pricing and customer satisfaction.
* **Deploy a predictive churn flag** in the CRM targeting customers who match the high-risk profile: month-to-month + Fiber Optic + no add-ons + tenure ≤12 months.

## Tools Used
* **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scipy)
* **Jupyter Notebook** for end-to-end analysis
* **Power BI** for dashboard

## Deliverables
* Cleaned and standardized dataset (`data_cleaned.csv`).
* Analysis notebook with cohort analysis, statistical testing, and feature correlation.
* Actionable business recommendations targeting high-risk customer segments.

## PowerBI Dashboard
Link to visualisations, insights and recommendations dashboard/report: https://app.powerbi.com/view?r=eyJrIjoiYTJlM2JkZmEtNzFkNS00NTUwLWE3Y2EtZTAyN2IwOGU1ZTk2IiwidCI6IjRiMWI5MDhjLTU1ODItNDM3Ny1iYTA3LWEzNmQ2NWUzNDkzNCIsImMiOjh9
