# palmora-hr-analysis
Capstone Project – Palmora Group HR Analysis (Power BI Dashboard). Completed as part of the Digital SkillUp Africa (DSA) Data Analysis Bootcamp.
# 👩‍💼 Palmoria Group HR Analysis

This Power BI dashboard was developed as part of the **Digital SkillUp Africa (DSA) Data Analysis Bootcamp Capstone Project**, focusing on HR-related data to uncover gender disparities, salary structures, bonus distribution, and compliance issues at Palmoria Group — a Nigerian manufacturing company.

## 📊 Project Overview

You were recruited as an HR Analytics expert to investigate critical workforce issues relating to gender equity, salary fairness, and bonus allocations. The objective was to identify trends and provide actionable recommendations to management before media scrutiny escalated further.

This project was completed using **Power BI**, leveraging:

* Power Query for data cleaning and transformation
* DAX for creating KPIs, salary bands, and bonus calculations
* Data modeling to link employee and bonus rule tables
* Interactive visuals including stacked bar charts, slicers, and KPI cards

## 🛠 Tools Used

* Microsoft Power BI Desktop
* Power Query Editor
* DAX Measures & Calculated Columns
* Report View with Slicers and Charts

## 📌 Key Tasks Performed

* Cleaned employee and department-level bonus data
* Removed employees with no salary or NULL department
* Assigned a generic gender label to undisclosed employees
* Created salary bands grouped in \$10,000 intervals
* Built KPIs for salary averages, bonus totals, rating distribution, and gender balance
* Developed multi-page interactive dashboards

### 💡 Key Insights (Detailed Narrative)

The Palmoria Group HR dataset comprises a total of **946 employees**, spread across **three regions** (Lagos, Abuja, and Kaduna) and multiple departments. A breakdown of gender reveals that **49.2% are male (465 employees)**, **46.6% are female (441 employees)**, and **4.2% (40 employees)** preferred not to disclose their gender.

Across all employees, the **average salary is $73,700**, while the **average performance rating is 3.14**. When analyzed by gender, **males earn an average of $75,000**, **females $72,000**, and **undisclosed gender employees earn slightly more at $78,000**. This trend continues geographically—**Lagos has the highest average salary at $75,800**, while **Abuja records the lowest at $72,000**. In terms of departmental pay, **Business Development leads with the highest average salary of $77,100**, whereas **Research & Development sits at the bottom with $68,400**.

A closer examination of wage compliance reveals that only **292 employees (30.9%)** earn above the national minimum threshold of $90,000. Of these, **152 are male (52.1% of high earners)**, **126 are female (43.2%)**, and **14 are undisclosed (4.8%)**. When translated into group-level percentages, **32.7% of male employees**, **28.6% of female employees**, and **35% of undisclosed gender employees** fall into the high-income bracket. Notably, the **Legal department** houses the **highest number of employees earning above $90k (31 employees)**, while **Research & Development has the fewest at just 16**. Regionally, **Kaduna leads with 111 high earners**, followed by Abuja and Lagos.

Bonus payouts add further dimension to the compensation story. A total of **$1.1 million in bonuses was distributed to female employees**, **$1 million to males**, and **$106,400 to employees with undisclosed gender**. Among departments, **Training received the highest bonus pool ($222,300)**, while **Accounting received the least ($156,900)**. **Kaduna again leads in regional bonus distribution**, taking home **$825,900**, while **Lagos received the smallest share at $572,200**.

Looking at salary bands in $10,000 intervals, the **largest concentration of employees (117 people or 12.4%)** falls within the **$70k–$80k** bracket. Conversely, only **26 employees (2.7%)** fall within the **$20k–$30k** range, indicating a relatively small proportion of very low earners and a salary structure centered around the mid-tier.

Performance analysis reveals slight but meaningful differences across groups. **Female employees scored an average rating of 3.2**, outperforming **male employees at 3.1**. **Employees with undisclosed gender had the highest average rating at 3.3**. Regionally, **Abuja posted the highest average performance rating of 3.21**, while **Lagos had the lowest at 3.08**. Departmentally, **Engineering led all others with an average rating of 3.30**, while **Product Management trailed behind with a 3.01 average**.

In terms of workforce size by department, **Product Management is the largest with 89 employees**, followed by Engineering and Marketing. **Marketing is the smallest department with only 65 employees**. The alignment between higher average salaries and stronger performance scores in departments like Business Development and Engineering highlights potential models for performance-driven compensation.

## 📂 Files Included

* `Palmora group analysis.pbix` – Full Power BI dashboard
* `screenshots/` – Dashboard previews

## 🎛 How to Use

1. Download `Palmora group analysis.pbix`
2. Open in Power BI Desktop
3. Use filters to explore by gender, salary band, and region
4. Interact with visuals and compare metrics across demographics

## 📚 Case Study Source

This project was completed as part of the **DSA Data Analysis Bootcamp Capstone**, fulfilling the requirements for **Case Study 3: Palmoria Group HR Analysis**.
