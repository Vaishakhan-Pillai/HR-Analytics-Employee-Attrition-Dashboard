# HR Analytics & Employee Attrition Dashboard

## Overview

An interactive, 2-page executive Power BI dashboard analyzing an HR workforce dataset of 1,470 employee records to diagnose and visualize organizational turnover trends — built to answer the question every HR and operations leader actually cares about: *who is leaving, why, and what can we realistically do about it.*

**Dataset:** 1,470 employee records
**Source:** IBM HR Analytics Employee Attrition dataset, Kaggle
**Tool:** Power BI Desktop

---

## Why This Project

Employee attrition is one of the most expensive, recurring problems a company faces — replacing an employee typically costs 6–9 months of their salary in recruiting, onboarding, and lost productivity. Most companies already *know* their attrition rate; what they usually don't have is a clear answer to *why* people are leaving and *which levers actually move the number*.

I chose this dataset specifically because it forces a shift from reporting ("attrition is 16.1%") to diagnosis ("attrition is 16.1%, and here are the three specific, fixable reasons why") — the same instinct I wanted to practice for BA/DA work generally: don't just visualize the data, find the lever a decision-maker can actually pull.

---

## Business Questions Answered

1. Which roles and departments carry the highest attrition risk?
2. At what point in an employee's tenure is turnover risk highest?
3. What's the single biggest actionable driver of attrition the company can address?
4. Does commute distance or job satisfaction meaningfully predict exit risk?
5. Which age groups and seniority levels are most vulnerable to leaving?

---

## Key Features & Objectives

- **ETL & Data Modeling:** Executed advanced ETL processes in Power Query, including data cleansing, removing zero-variance attributes, and building custom conditional age demographics to optimize storage and data processing.
- **Advanced DAX:** Developed custom measures (Attrition Counts, Retention Rates, and Salary Averages) to expose high-risk pockets within the organization.
- **Actionable Insights:** Revealed key turnover catalysts, such as overtime workload imbalances, enabling data-driven retention strategies.

**Tech Used**
- **Tools:** Power BI, Power Query, DAX
- **Techniques:** Data Cleaning, Relational Data Modeling, Interactive Data Visualization

---

## Dashboard Preview

### Page 1 — HR Overview
![image alt](https://github.com/Vaishakhan-Pillai/HR-Analytics-Employee-Attrition-Dashboard/blob/main/Page%201.png?raw=true)

**Key Findings**
- **Sales Representatives quit far more often than anyone else — nearly 4 in 10 leave.** Their attrition rate (39.8%) is close to 2.5× the company average. Lab Technicians and HR staff aren't far behind. *What this means for the company:* front-line, customer-facing roles need retention attention first — a generic, company-wide retention policy will miss where the real bleeding is.
- **Two-thirds of the entire company works in R&D.** With 961 of 1,470 employees (65.4%) in R&D versus just 63 in HR, R&D isn't just one department among several — it *is* the company. *What this means for the company:* even a small percentage improvement in R&D retention saves more people, and more cost, than a large improvement anywhere else.
- **Most people who quit do it in their first five years.** The data shows attrition risk peaks early in someone's tenure, then drops off sharply. *What this means for the company:* the highest-value fix isn't a company-wide raise — it's a stronger onboarding and early-career support program, since that's where people are actually walking out the door.
- **Managers and senior staff almost never leave — under 5% attrition.** Seniority and role security are strongly linked to staying. *What this means for the company:* the problem isn't "people leave this company" broadly — it's concentrated in specific early-career and front-line roles, which is good news, because it means the fix can be targeted rather than expensive and company-wide.

### Page 2 — Sentiment & Attrition Drivers
![image alt](https://github.com/Vaishakhan-Pillai/HR-Analytics-Employee-Attrition-Dashboard/blob/main/Page%202.png?raw=true)

**Key Findings**
- **Overtime is the single biggest reason people quit.** Employees working overtime leave at roughly 3× the rate of everyone else (~30% vs ~10%). *What this means for the company:* this is the cheapest, fastest lever available — fixing workload distribution costs far less than losing and replacing an employee, and this is the one finding leadership can act on immediately.
- **Long commutes quietly push people out the door.** Attrition stays fairly flat for shorter commutes, then jumps sharply — up to ~42% — once someone's commute passes 22–25 km. *What this means for the company:* this is a solvable, low-cost fix — remote/hybrid flexibility or relocation support for long-commute employees could meaningfully cut turnover in that group specifically.
- **Unhappy employees leave at nearly double the rate of satisfied ones.** Employees who rated their job satisfaction lowest left at almost 2× the rate of the most satisfied group. *What this means for the company:* pay isn't the whole story — day-to-day job quality and management matter just as much, if not more, for keeping people.
- **Younger employees (25–35) are the most likely to leave overall.** This age group shows both the largest headcount and the most visible attrition. *What this means for the company:* early-career employees are the most mobile and the most exposed to competitor offers, making them the group most worth investing retention effort in early.

---

## Files

| File | Description |
|---|---|
| `IBM-HR-DATA-Dashboard.pbix` | Full Power BI project — data model, ETL steps, DAX measures, and both dashboard pages |
| `Raw-HR-Employee-Attrition.csv` | Raw dataset |
| `Page 1.png` / `Page 2.png` | Dashboard exports |

---

## Note on Workflow

Used Claude to help frame the business questions this dashboard set out to answer, and Gemini for early visual layout ideas. All ETL steps, DAX measures, and the final dashboard were built and tested independently in Power BI Desktop.


