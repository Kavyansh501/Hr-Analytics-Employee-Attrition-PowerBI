# HR-Analytics-Employee-Attrition-PowerBI

## Dashboard Preview
Interactive HR Analytics and Employee Attrition Dashboard built using Power BI, DAX, Power Query, and Excel.

## HR Analytics & Employee Attrition Dashboard - Power BI

### Project Overview
Analyzed employee-level HR data to understand workforce composition, employee attrition patterns, and key factors associated with attrition.

The dashboard provides an interactive view of employee attrition across departments, job roles, gender, age groups, overtime, salary bands, distance bands, satisfaction levels, performance ratings, and years at the company.

### Key Features

**HR Overview:** Total Employees, Attrition Count, Attrition Rate, and Average Salary

**Attrition Analysis:** Attrition analysis across Department, Gender, Job Role, Age Group, Overtime, Salary Band, Distance Band, Satisfaction Levels, Performance Rating, and Years at Company

**Drill-through Navigation:** Navigate from summary visuals to the Employee Details page for detailed employee-level analysis

**HR Insights Tooltip:** Report-page tooltip providing contextual HR metrics for dashboard visuals

**Interactivity:** Department, Gender, Job Role, Overtime, and Year slicers

**Reset Filters:** Bookmark-based Reset Filters button for quickly restoring default slicer selections

**Tools:** Excel, Power Query, Power BI, DAX Measures, Data Modeling

### Dashboard Pages

**HR Overview**
- Overall workforce and attrition KPIs
- Attrition by Department
- Attrition by Gender
- Attrition by Age Group
- Attrition by Job Role
- Attrition trend by YearMonth

**Attrition Analysis**
- Attrition by Overtime
- Attrition by Salary Band
- Attrition by Distance Band
- Attrition by Job Satisfaction
- Attrition by Environment Satisfaction
- Attrition by Performance Rating
- Attrition by Years at Company

**Employee Details**
- Employee-level details through drill-through
- Employee demographics, role, salary, tenure, overtime, and attrition information

**HR Insights Tooltip**
- Context-sensitive Total Employees
- Attrition Count
- Attrition Rate
- Average Salary

### Data Modeling

**FactEmployee:** Main employee-level fact table containing workforce and attrition data

**DimJob:** Dimension table created from employee job attributes

**DimDate:** Custom date table connected to FactEmployee[Hire_Date]

**Relationships:**
- DimJob → FactEmployee
- DimDate → FactEmployee

### DAX Measures

Created reusable DAX measures including:
- Total Employees
- Active Employees
- Attrition Count
- Attrition Rate
- Average Salary
- Average Age
- Average Years at Company
- Average Job Satisfaction
- Average Environment Satisfaction
- Average Performance Rating

Additional dynamic DAX title measures were implemented to make chart titles respond to slicer selections.

### Data Preparation

**Excel:** Source employee dataset

**Power Query:** Data cleaning, transformation, duplicate handling, and preparation for analysis

**Power BI:** Data modeling, DAX calculations, interactive visualizations, drill-through, tooltips, and dashboard design
