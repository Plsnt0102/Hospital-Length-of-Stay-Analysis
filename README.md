Hospital Length of Stay (LOS) Analysis

Project Overview
This project analyzes hospital Length of Stay (LOS) to identify patterns, understand key drivers of prolonged admissions, and present insights through an interactive Excel dashboard. The goal is to support operational efficiency and clinical decision-making using data-driven insights.

Project Objective

•	Explore hospital LOS patterns
•	Identify factors influencing prolonged hospital stays
•	Develop an interactive Excel dashboard for analysis and reporting

Dataset Overview

•	Records: 100,000
•	Features: 28
•	Primary Metric: Length of Stay (LOS)  https://www.kaggle.com/datasets/aayushchou/hospital-length-of-stay-dataset-microsoft   
•	Key Dimensions: Gender, Visit Frequency, Facility, Discharge Status, Clinical Indicators
All data fields were reviewed for consistency, accuracy, and usability prior to analysis.

Data Cleaning & Preprocessing

Minimal preprocessing was required:

•	No missing values detected
•	No duplicate records found
•	Date fields standardized to proper date format
•	Numeric fields (including LOS) converted to whole numbers
Feature Engineering
The following derived fields were created:
•	LOS Bins: 0–2, 3–5, 6–10, >10 days
•	Visit Frequency: Single vs. Repeat visits
•	Repeat Visit Flag: For KPI calculations
•	Simplified Discharge Status: For aggregation


Key Performance Indicators (KPIs)

•	Average Length of Stay
•	Median Length of Stay
•	Discharge Rate
•	Repeat Visit Rate
All KPIs are dynamically linked to PivotTables and update automatically with slicer selections.

Exploratory Data Analysis & Visualizations
The interactive Excel dashboard includes:
•	LOS distribution analysis
•	Average LOS by visit frequency
•	Average LOS by gender
•	Discharge counts by LOS category
•	Average LOS by facility
Slicers allow filtering by gender, visit frequency, facility, and LOS category.

Key Insights

•	Most patients have short hospital stays, while a small group accounts for prolonged LOS
•	Repeat visits are strongly associated with longer LOS
•	Discharge probability decreases as LOS increases
•	Facility-level variation suggests opportunities for benchmarking

Recommendations

•	Focus care management efforts on repeat-visit patients
•	Review long-stay cases to enable early intervention
•	Benchmark facility performance to identify best practices
•	Improve post-discharge planning to reduce readmissions

Tools Used

•	Microsoft Excel (PivotTables, Power Pivot, Slicers, Dashboard Design)




Deliverables

•	Interactive Excel Dashboard
•	Cleaned Dataset
•	Project Documentation

Conclusion

This project demonstrates how Excel-based analytics can uncover actionable insights into hospital operations. The dashboard enables stakeholders to monitor LOS drivers, optimize patient flow, and support data-driven healthcare decisions.

KPI Cards
<img width="1308" height="180" alt="KPI Cards" src="https://github.com/user-attachments/assets/b665af3a-5cb0-48b0-9136-7c5028e08b8f" />

Key performance indicators summarizing overall hospital length of stay, discharge outcomes, and repeat visit behavior.

Length of Stay Distribution
<img width="848" height="523" alt="LOS Distribution" src="https://github.com/user-attachments/assets/61f8a4fa-8c31-4fa5-8509-a1bd5e5d2a3d" />


Most patients experience short hospital stays, while a small proportion account for prolonged lengths of stay.

Average Length of Stay by Facility

<img width="818" height="526" alt="LOS by Facid" src="https://github.com/user-attachments/assets/5badc863-49cb-4638-93fa-24953e054918" />


Average length of stay varies across facilities, highlighting differences in patient mix and operational practices.

Length of Stay Analysis Dashboard

<img width="900" height="585" alt="Dashboard view" src="https://github.com/user-attachments/assets/5faf9c39-ce1a-456e-b3e5-ededd5d0caff" />



The interactive Excel dashboard contains slicers, dynamic KPIs, and PivotTables to explore hospital Length of Stay (LOS) patterns.  

 Important: Due to limitations in Excel Online, interactive features (slicers and dynamic KPI cards) will not function properly in the browser.  

To view the dashboard fully:  
1. Download the Excel file using the link below.  
2. Open the file in Excel Desktop to access all interactive features.  


Click thr link below to download
https://docs.google.com/spreadsheets/d/1voBCf3omgfuRiyn6suM9Tves--qO9jsJ/edit?usp=drive_link&ouid=103507646127850573091&rtpof=true&sd=true






