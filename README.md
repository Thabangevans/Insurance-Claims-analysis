# Insurance-Claims-analysis

# Insurance Claims Analysis Project

## Project Purpose
This project is dedicated to analyzing **customer, policy and claims data** in order to uncover key business challenges such as:
- Increasing claim costs
- Suspected fraudulent claims
- Low customer retention

The ultimate goal is to recommend **data-driven actions** that support decision-making, improve profitability and reduce risk.  


---

## Objectives(Tools used)
- Apply **Databricks: data cleaning and validation** to ensure reliable analysis.
- Build **Databricks: SQL queries** for claims, fraud and customer insights.
- Design **Power BI: dashboards** that highlight KPIs and trends in a clear, executive-ready format.
- Use **Documentation: data storytelling** to connect findings with actionable business recommendations.

---

## Key Insights
1. **What trends do we observe?**  
   • Claims volume: Between February – April in both years 2024–2025, we notice a spike increase in claims. This shows a repeating pattern which may be a result of seasonal behavior. The rest of the chart remains increasing and decreasing in a stable manner.
   
   • Fraud presence: We see Fraud presence across the entire dataset; it is not a one-time event, but they consistently occur.
   
   • Claim Status: Majority of claims are approved, but some are rejected or pending due to the possibility of the company thoroughly checking for fraud.

3. **Which policy type is most risky?**  
   • Motor and Life are the riskiest policies to take for individual reasons, for example;
   
   • Motor Policy has the second highest Fraud flag and a very high sum in claim amounts; Motor Policies are often taken advantage of because repair prices can be inflated.
   
   • Life Policy, even though it is lesser than most policies when it comes to fraud flags, it still has the highest claims amount than all the other policies. This policy usually has a high pay out, attracting fraud attempts.

5. **Where is fraud most common?**  
   • Fraud happens everywhere but mostly common in North West and Western Cape.
   
   • Western Cape has the highest fraud flag and one of the highest claim amounts in Life, Home and Motor policies, thus making it the main hotspot.

7. **Which customers or segments are high-risk?**  
   • Young adults (Age 19-40): More fraudulent cases are linked to this age group.
   
   • Lapsed or cancelled policies: Fraud often happens when a policy is about to end.
   
   • Premium vs Claim outliers: Clients who pay low premiums but claim very high amounts are risky.

---

## 🔹 Recommendations

### Fraud Prevention strategies:
• Improve data collection processes to reduce “unknown” values.

• Introduce stronger fraud detection systems, especially Motor and Life policies.

• Flag lapsed/cancelled policies for extra review before payout.

• Focus on fraud monitoring resources in North West and Western Cape more closely.

### Pricing Adjustments:
• Increase premiums for Motor and Life policies because they reflect high claim amounts.

• Offer discounts for consistent premium payers.

• Adjust pricing models to reflect fraud hotspots based on Province.

### Customer Targeting strategies:
• Target low-risk clients with loyalty rewards (older, stable policyholders).

• Improve onboarding processes to reduce missing data.

• Educate young adults on fraudulent consequences and benefits of responsible claims of behavior.

---

## Dashboard Design
• **Top row**: KPI cards (Total Customers, Total Claims, Total Claim Amount, Fraud Cases).  
• **Middle row**: Claims Analysis (Policy Type, Over Time, Status Breakdown).  
• **Second Middle row**: Fraud Insights and Customer Insights (Fraud vs Non-Fraud, Location, Policy type).  
• **Bottom row**: Claims Analysis (Age, Gender, Premium vs Claims)

---

## Disclaimer
• The dataset used is **synthetic** and was intentionally designed with data quality issues to simulate real-world scenarios.

---

## Author
Thabang Evans Pholo
