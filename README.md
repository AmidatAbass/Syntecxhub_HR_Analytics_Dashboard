# Syntecxhub_HR_Analytics_Dashboard
Project Overview

This project analyzes a 1,000-employee HR dataset to understand employee attrition and identify workforce patterns that can support HR decision-making.

The analysis focuses on employee characteristics including department, job role, salary, experience, job satisfaction, overtime, workload, and attrition.

-The final output is an interactive Power BI dashboard supported by Excel-based analysis.

-This project was completed as part of the Syntecxhub HR Analytics Dashboard (Project 3).

**Objectives**
- Analyze employee data, particularly salary, department, and experience.
- Identify patterns in employee attrition.
- Perform correlation analysis to examine relationships between selected numerical factors and attrition.
- Compare attrition across departments and job roles.
- Calculate key HR KPIs including attrition and retention rates.
- Build an HR dashboard for decision-making.

**Dataset**
The dataset contains 1,000 employee records and 27 columns covering employee demographics, job information, compensation, experience, satisfaction, workload, and attrition-related information.
Key Fields Used
- "Department"
- "Job_Role"
- "Job_Level"
- "Monthly_Income"
- "Salary_Group"
- "Years_at_Company"
- "Years_in_Current_Role"
- "Experience_Group"
- "Job_Satisfaction"
- "Performance_Rating"
- "Training_Hours_Last_Year"
- "Overtime"
- "Avg_Hours_Worked_Per_Week"
- "Absenteeism"
- "Work_Environment_Satisfaction"
- "Attrition"

**Derived Fields**
- "Overtime Numeric"
- "Attrition Numeric"
- "Experience Group"

Data Preparation & Analysis
The dataset was prepared and analyzed in Microsoft Excel. The process included:
- Reviewing and organizing the employee data.
- Creating salary and experience groups for comparison.
- Converting "Overtime" from Yes/No into a numeric field for correlation analysis.
- Converting "Attrition" into a numeric field for correlation analysis.
- Using pivot tables to compare employee attrition across departments and other categories.
- Calculating correlations between attrition and selected numerical factors.

**Key KPIs**
KPI| Value
Total Employees| 1,000
Employees Left| 189
Employees Stayed| 811
Attrition Rate| 18.90%
Retention Rate| 81.10%

**Key Findings**
Department
- IT has the highest departmental attrition rate at 21.26%.
- HR follows at 20.85%.
- Sales has the lowest departmental attrition rate at 17.09%.

-Job Role
The dashboard compares employees who left across Executive, Manager, Assistant, and Analyst roles.
Executive and Manager roles have the highest numbers of employees who left in the role comparison.
-Salary
The 5K–9.9K salary group has the highest number of employees who left in the salary-group comparison.
-Age
Attrition is compared across five age groups:
- Under 25
- 25–34
- 35–44
- 45–54
- 55+

**Experience**
Employees are grouped into:
- 0–2 years
- 3–5 years
- 6–10 years
- 11–15 years
- 16+ years
The 16+ years group has the highest number of employees who left in the experience-group comparison.

**Correlation Analysis**
Factor| Correlation with Attrition
Age| 0.0292
Monthly Income| 0.0119
Years at Company| 0.0229
Years in Current Role| -0.0140
Job Satisfaction| 0.0134
Overtime Numeric| -0.0165
All correlations are very close to zero, indicating very weak linear relationships between the tested numerical factors and attrition.
«Correlation does not establish causation; these results only describe linear association within this dataset.»

**Dashboard**
The Power BI dashboard includes:
- KPI cards for total employees, employees who left, employees who stayed, attrition rate, and retention rate.
- Attrition by Department.
- Attrition by Job Role.
- Attrition by Salary Group.
- Attrition by Age Group.
- Attrition by Experience Group.
- Department and Job Role slicers for interactive filtering.
- A Key Insights section summarizing the main findings.

Tools Used;
**Microsoft Excel**
Used for:
- Data preparation
- Calculations
- Pivot tables
- Correlation analysis

**Power BI Desktop**
Used for:
- KPI measures
- Dashboard visuals
- Interactive filtering
- Dashboard design

**GitHub**
Used for:
- Project documentation
- Portfolio storage

**Project Files**
- Cleaned Employee Attrition Dataset — prepared dataset used for the analysis.
- Power BI Dashboard (.pbix) — interactive HR analytics dashboard.
- Dashboard Screenshot — preview of the completed dashboard.

**Conclusion**
-The dataset has an overall 18.90% attrition rate and 81.10% retention rate across 1,000 employees.
-IT records the highest departmental attrition rate at 21.26%, while the salary, age, job-role, and experience comparisons show where employee exits are concentrated.
-The correlation analysis shows very weak linear relationships between the selected numerical factors and attrition. Therefore, no single tested numerical factor strongly explains employee attrition in this dataset.

The Power BI dashboard brings these findings together in an interactive format that allows users to explore attrition by department and job role.
