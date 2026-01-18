# HR Analytics Power BI Report

##  Project Overview
This project is an **HR Analytics Power BI report** created as part of my data analytics portfolio. The goal of this report is to provide meaningful insights into workforce trends and support data-driven HR decision-making.

The report focuses on three key HR areas:

* Employee Headcount
* Employee Retention
* Employee Turnover

## Key Features & Analysis

### 1️) Employee Headcount Analysis

The Headcount report page provides a comprehensive overview of the current workforce.

Visuals included:

* Headcount by Job Level
* Headcount by Department
* Headcount by Location
* Headcount by Employee Demographics(such as age group, gender, etc.)

This page helps stakeholders understand workforce distribution across different organizational dimensions.

---

### 2️) Employee Retention Analysis

The Retention report page focuses on understanding how well the organization retains employees over time.

Visuals and interactions included:

* Retention trends by Year
* Retention analysis by Job Level
* A **dynamic slicer parameter** that allows users to select different employee demographics
* An interactive **line chart** that updates based on the selected demographic parameter

This approach enables flexible analysis and deeper insights into retention patterns across various employee segments.

---

### 3️) Employee Turnover Analysis

The Turnover report page analyzes employee exits and attrition trends.

Visuals included:

* Turnover by Year
* Turnover by Job Level
* Turnover by Termination Type
* Turnover by Termination Reason
* A detailed table visual displaying:

  * Employee Name
  * Termination Date
  * Department
  * Count of Departing Employees

This page helps identify key drivers of employee turnover and areas requiring HR intervention.


## Data Model and Relationships

![Power BI Data Model](https://github.com/Dhanashri-Karve/HR-Analytics-Report/blob/main/Data%20Model%20and%20Relationship%20Preview.png)

Model Design Overview
People_Fact acts as the central fact table, containing employee-level records such as employment status, hire date, active status, and foreign keys.
Multiple dimension tables are connected to the fact table using one-to-many (1:*) relationships, enabling flexible slicing and filtering.

Dimension Tables

- Demographic_Dim – age and age group attributes
- Department_Dim – department and sub-department details
- Job_level_Dim – employee job levels
- Education_Dim – education background
- Marital_Dim – marital status
- Location_Dim – employee location and city
- Manager_Dim – reporting manager information
- Term_Dim – termination type and reason
- Date – calendar table used for time-based analysis (year, month, weekday, timeframe)

##  Interactive Features

* A **slicer panel** created using **bookmarks** for improved user experience
* Clean and intuitive navigation across report pages
  

##  Data Preparation & Modeling

The following steps were performed as part of the project:

* Data exploration to understand structure and quality
* Data cleaning to handle missing values and inconsistencies
* Data manipulation and transformation using Power Query
* Creation of calculated columns and measures using DAX
* Data modeling to ensure accurate relationships and performance


##  Tools & Technologies Used

* Power BI (Data Modeling, DAX, Visualizations, Bookmarks, Slicers)
* Power Query (Data Cleaning & Transformation)


##  Project Objective

The objective of this project is to demonstrate my ability to:

* Analyze HR data effectively
* Build interactive and user-friendly Power BI dashboards
* Translate business questions into actionable insights
* Apply best practices in data preparation and visualization

##  Preview
![Power BI Data Model](https://github.com/Dhanashri-Karve/HR-Analytics-Report/blob/main/HR%20Analytics%20Report%20Preview.png)

https://github.com/Dhanashri-Karve/HR-Analytics-Report/blob/main/HR%20Analytics%20Report%20Preview.png



