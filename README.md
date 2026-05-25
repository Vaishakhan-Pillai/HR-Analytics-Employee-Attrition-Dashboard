# HR Analytics & Employee Attrition Dashboard

**Overview**
Designed an interactive, 2-page executive Power BI dashboard analyzing an HR workforce dataset of 1,470 records to diagnose and visualize organizational turnover trends. 

**Key Features & Objectives**
*   **ETL & Data Modeling:** Executed advanced ETL processes in Power Query, including data cleansing, removing zero-variance attributes, and building custom conditional age demographics to optimize storage and data processing.
*   **Advanced DAX:** Developed custom measures (Attrition Counts, Retention Rates, and Salary Averages) to expose high-risk pockets within the organization.
*   **Actionable Insights:** Revealed key turnover catalysts, such as overtime workload imbalances, enabling data-driven retention strategies.

**Tech Used**
*   **Tools:** Power BI, Power Query, DAX
*   **Techniques:** Data Cleaning, Relational Data Modeling, Interactive Data Visualization

**Dashboard Preview**
**Page 1 - HR Overview**
![image alt](https://github.com/Vaishakhan-Pillai/HR-Analytics-Employee-Attrition-Dashboard/blob/main/Page%201.png?raw=true)
**Key findings**
*  **Sales Representatives are most at-risk - 39.8% attrition rate** - Nearly 2.5× the company average. Laboratory Technicians (23.9%) and HR staff (23.1%) follow. Front-line and specialist roles face the highest churn pressure.
*  **R&D dominates headcount - 961 employees (65.4%)** - 
R&D is by far the largest department. Sales has 446 (30.3%) and HR only 63 (4.3%). Talent retention in R&D carries disproportionate org-wide risk.
*  **Early-tenure attrition is the biggest risk - Years 1–5 show peak exits** - 
The "Tenured Attrition Cohort" chart shows the highest Yes-attrition bars concentrated in the first 5 years at the company, a classic early-tenure flight risk pattern.
*  **Stable roles show near-zero attrition - Managers & Directors < 5%**
Managers, Healthcare Representatives, and Research Directors have the lowest attrition, suggesting seniority and role security significantly reduce turnover intent.

**Page 2 - Sentiment & Attrition Drivers**
![image alt](https://github.com/Vaishakhan-Pillai/HR-Analytics-Employee-Attrition-Dashboard/blob/main/Page%202.png?raw=true)
**Key Findings**
*  **Overtime is the single strongest attrition driver - ~30% vs ~10% attrition rate** -
Employees who work overtime are 3× more likely to leave. This is the clearest actionable lever. Workload redistribution could directly reduce the 16.1% headline rate.
*  **Distance from home spikes attrition at 22–25 km - ~42% attrition at peak** - 
Attrition rate is relatively stable at 10–20% for short commutes, then spikes sharply around 22–25 km. Commute friction is a measurable, addressable retention factor.
*  **Low job satisfaction doubles exit rate - Score 1: 66 exits (22.8%)** - 
Satisfaction score 1 had 66 attritions out of 289 employees — nearly double the rate of score 4 (52 out of 459 = 11.3%). Job quality, not just pay, drives exits.
*  ** The 25–35 age group has the highest absolute attrition - Largest "Yes" attrition bar** - 
The 25–35 cohort shows the largest total headcount and the most visible attrition segment. Early-career employees are mobile and the most vulnerable to competitor offers.
