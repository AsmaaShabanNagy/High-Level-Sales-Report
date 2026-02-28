Sales & Marketing Analytics - Power BI Graduation Project
📌 Project Overview
This repository contains the final graduation project for the Data Analytics Diploma. The project focuses on building two distinct analytical dashboards: a Strategic Dashboard for C-level executives and an Operational Dashboard for the sales team. The goal was to transform raw dummy sales data into actionable insights using advanced Power BI techniques.
+2

🛠️ Key Technical Features
1. Advanced DAX & Time Intelligence

Dynamic Comparisons: Developed measures to compare monthly trends (Ordered vs. Delivered Amount).


Multi-Year Tooltips: Created custom tooltips that display values for the last three years of a selected month (e.g., hovering over May 2024 shows data for 2022, 2023, and 2024).


Flexible Date Slicing: Implemented single-select slicers for Years, Months, and specific Days to drive dynamic reporting.
+1

2. Efficiency via Calculation Groups (Question 4)

Problem: The requirement called for 5 key KPIs (Total Revenue, Profit, Margin %, etc.), each requiring 5 different time-based variations (LY, LY YTD, Target, etc.).


Solution: Instead of writing 25 separate DAX measures, I utilized Calculation Groups to apply time intelligence logic across all base measures, significantly reducing development effort and improving model maintainability.

3. Row-Level Security (RLS)
Implemented a robust security model to restrict data access based on user roles:
+1


User A: Access to the entire "TV and Video" category.


User B: Access only to the "Car Video" sub-category within "TV and Video".
+1

4. User Experience & Visual Analytics

Conditional Formatting: Used visual cues to highlight "Over Achieving" vs. "Under Achieving" KPIs dynamically based on targets.
+1


Contextual Highlighting: Designed charts where selecting a specific month visually highlights it while keeping other months visible for context.


Marketing Deep-Dive: Created a dedicated visual for marketing indicators (Impressions) with three selection modes: YTD, Time Range (Last 15/30/45 days), and Custom Manual Periods.
+2

5. Advanced Interactivity

Drill-through: Enabled country-level sales analysis with drill-through capabilities to view historical performance across all years, regardless of the main page filters.


Percentage of Continent: Table visuals showing each country's sales as a percentage of their respective continent's total, unaffected by country-level slicers.

📂 Repository Content

Sales Analysis.pbix: The main Power BI project file on power bi service [https://app.powerbi.com/groups/me/reports/91bacdee-ec1c-4652-9495-53dfd8a7c4b5/2fc4780039f9e52d34d1?experience=power-bi]
& from drive[https://drive.google.com/file/d/1wF3RKhGdqSL56OA9dgXg7HkQX20uWd9U/view?usp=sharing].

👥 Credits & Acknowledgments
Teammates: Special thanks to Nada and Mohamed for their collaboration.

Instruction: Grateful to Eng. Hamdy (Instructor) and Eng. Hagar (Mentor) for their invaluable guidance throughout the diploma.
