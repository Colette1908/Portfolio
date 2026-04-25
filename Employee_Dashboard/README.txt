# Employee Data Cleaning & Workforce Analytics Dashboard

A professional end-to-end data analytics portfolio project focused on **data cleaning, workforce reporting, employee performance analysis, and executive dashboard design** using Power BI.

---

# Project Overview

This project demonstrates how messy employee data can be transformed into a clean, analysis-ready dataset and converted into interactive dashboards for business decision-making.

The solution includes:

* Automated data cleaning workflow
* Executive workforce dashboard
* Employee performance dashboard
* KPI reporting
* Department comparisons
* Leave analysis
* Interactive slicers and tooltips

---

# Business Problem

Many organisations store employee data in spreadsheets or manual systems with issues such as:

* Duplicate records
* Missing values
* Invalid emails
* Inconsistent text formatting
* Mixed date formats
* Limited reporting visibility

Without clean data, management cannot make reliable workforce decisions.

---

# Solution

Built a complete reporting solution that:

1. Cleans and standardises raw employee data
2. Fixes data quality issues
3. Creates reusable metrics with DAX
4. Delivers executive dashboards in Power BI
5. Supports filtering and drill-down analysis

---

# Tools Used

* Microsoft Excel
* Power Query
* Power BI
* DAX

---

# Dataset

Synthetic employee dataset created for portfolio purposes.

### Fields Included

* EmployeeID
* EmployeeName
* Department
* JoinDate
* Email
* Salary
* HoursWorked
* LeaveType

---

# Data Cleaning Performed

Using Power Query, the following transformations were applied:

* Removed duplicate records
* Trimmed spaces
* Standardised employee names
* Standardised department names
* Converted mixed date formats
* Replaced blanks with null values
* Flagged invalid email addresses
* Corrected numeric data types
* Prepared clean model for reporting

---

# Dashboards Included

# 1. Workforce Executive Dashboard

Provides high-level workforce insights:

### KPIs

* Number of Employees
* Average Salary
* Total Hours Worked
* Invalid Emails
* People on Leave

### Visuals

* Employees by Department
* Salary by Department
* Hours Worked Frequency
* Leave Type Breakdown
* New Hires by Month
* Employee Detail Table

---

# 2. Employee Performance Dashboard

Provides deeper employee productivity insights:

### KPIs

* Highest Hours Worked
* Lowest Hours Worked
* Avg Hours per Employee
* Employees Below Target
* Top Performing Department

### Visuals

* Top Employees by Hours
* Hours by Department
* Salary vs Hours Scatter Plot
* Hours Worked by Month

---

# Key Insights

Examples from the analysis:

* IT recorded the highest total hours worked
* Finance had the highest average salary
* Several records contained invalid email addresses
* March had the highest onboarding activity
* Six employees were below target hours

---

# Files Included

Recommended repository structure:

```text id="w7b4nm"
Employee-Workforce-Dashboard/
│── README.md
│── Employee_Dashboard.pbix
│── Raw_Employee_Data.xlsx
│── Cleaned_Employee_Data.xlsx
│── images/
│   ├── dashboard_page1.png
│   ├── dashboard_page2.png
│── dax/
│   ├── measures.txt
```

---

# Screenshots

Add exported dashboard screenshots here.

Example:

```markdown id="l6h1ea"
![Workforce Dashboard](images/dashboard_page1.png)
![Employee Performance Dashboard](images/dashboard_page2.png)
```

---

# Example DAX Measures

## Total Employees

```DAX id="ie90qo"
Total Employees = DISTINCTCOUNT(employee_data[EmployeeID])
```

## Total Hours

```DAX id="4q7fjd"
Total Hours = SUM(employee_data[HoursWorked])
```

## Invalid Emails

```DAX id="2y9rpl"
Invalid Emails =
CALCULATE(
COUNTROWS(employee_data),
employee_data[Email_Clean] = "Invalid"
)
```

---

# Why This Project Matters

This project demonstrates practical business skills that employers value:

* Data cleaning
* Data modeling
* KPI development
* Dashboard design
* Business storytelling
* Power BI reporting
* Attention to detail

---

# How to Use

1. Download the `.pbix` file
2. Open in Power BI Desktop
3. Refresh data if needed
4. Use slicers to explore insights

---

# Future Enhancements

Potential upgrades:

* Department drillthrough pages
* Row-level security
* Monthly trend comparisons
* Automated refresh
* SQL database backend
* Predictive workforce analytics

---

# About Me

Data analyst with extensive business and management experience focused on building practical analytics solutions that improve decision-making.

---

# Connect

Add your:

* LinkedIn profile
* GitHub profile
* Portfolio link

---

# License

Portfolio project for demonstration purposes.
