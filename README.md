# Employee Attendance Analytics Dashboard Using Microsoft Excel

## Project Overview

This project presents an interactive **Employee Attendance Analytics Dashboard** developed using Microsoft Excel.

The dashboard analyses employee attendance patterns, leave utilisation, work arrangements and punctuality across different departments in Bangalore during **Q1 2026 (January to March)**.

The objective is to transform raw employee attendance records into meaningful HR insights using data cleaning, PivotTables, PivotCharts, KPI calculations and interactive filtering.

## Dashboard Preview

![Employee Attendance Analytics Dashboard](images/dashboard.png)

## Project Objectives

- Analyse employee attendance patterns across three months.
- Monitor present, half-day and leave records.
- Compare attendance rates across departments.
- Analyse monthly attendance trends.
- Explore employee work-mode distribution.
- Examine leave categories and utilisation.
- Identify departmental differences in late arrivals.
- Develop an interactive and user-friendly HR analytics dashboard.

## Key Performance Indicators

The dashboard includes six KPIs:

| KPI | Value |
|---|---:|
| Total Employees | 980 |
| Total Attendance Records | 55,374 |
| Present Records | 51,553 |
| Half Day Records | 1,186 |
| On Leave Records | 2,635 |
| Present Rate | 93.10% |

### Present Rate Calculation

Present Rate = (Present Records / Total Attendance Records) × 100

Present Rate = (51,553 / 55,374) × 100 = 93.10%

The Present Rate represents the proportion of recorded attendance entries marked Present. It is not a calendar-based attendance percentage.

## Dashboard Visualisations

### 1. Attendance Status Distribution

A doughnut chart illustrating the proportion of employee attendance records classified as:

- Present
- Half Day
- On Leave

This visualisation provides an overview of the attendance status distribution.

### 2. Monthly Attendance Trend

A line chart comparing Present, Half Day and On Leave records across January, February and March 2026.

This allows users to observe monthly changes in attendance patterns.

### 3. Department-wise Attendance

A 100% stacked bar chart comparing attendance distributions across departments.

The chart displays the percentage of Present, Half Day and On Leave records within each department, allowing comparisons despite differences in departmental record volumes.

### 4. Work Mode Distribution

A stacked column chart comparing attendance records across:

- Work From Office
- Work From Home
- Client Site

This visualisation helps analyse how recorded working arrangements vary by month.

### 5. Department-wise Late Arrivals

A horizontal bar chart displaying average late-arrival minutes across departments.

The analysis provides a comparative view of punctuality patterns among recorded working days.

### 6. Leave Type Distribution

A horizontal bar chart showing the distribution of recorded leave categories, including:

- Casual Leave
- Sick Leave
- Earned Leave
- Parental Leave
- Marriage Leave
- Bereavement Leave
- Loss of Pay
- Work From Home-related leave

This visualisation helps identify the frequency of different leave categories.

## Interactive Dashboard Features

The dashboard includes five interactive controls.

| Interactive Filter | Purpose |
|---|---|
| Attendance Date Timeline | Filter attendance by month |
| Department Slicer | Analyse department-wise patterns |
| Gender Slicer | Compare attendance across recorded gender categories |
| Work Mode Slicer | Analyse work arrangements |
| Shift Type Slicer | Compare attendance across different shifts |

The Excel Timeline allows users to navigate chronologically through the reporting period.

Compatible PivotTables and PivotCharts are connected using Excel Report Connections.

These features enable users to explore different segments of the attendance dataset without manually modifying the underlying data.

## Tools and Technologies Used

**Microsoft Excel**

- Power Query
- Excel Data Model
- PivotTables
- PivotCharts
- Slicers and Timeline
- Distinct Count
- Data cleaning and transformation
- Conditional formatting and custom chart formatting
- Excel formulas and percentage calculations

## Data Cleaning and Preparation

The original CSV dataset was imported into Excel and processed using Power Query.

The data preparation process included:

1. Importing employee attendance records from CSV.
2. Validating column data types.
3. Checking for duplicate records.
4. Identifying missing login and logout timestamps.
5. Reviewing missing values associated with leave records.
6. Cleaning text columns using Trim and Clean.
7. Creating additional Month, Day Name and Month-Year fields.
8. Loading the transformed data into Excel.
9. Creating PivotTables for further analysis.

Missing login and logout values corresponding to employee leave were retained instead of being automatically removed or replaced.

## Data Analysis Methodology

The analysis was conducted through the following stages.

### Stage 1: Data Preparation

Imported, reviewed and cleaned the dataset using Power Query.

### Stage 2: KPI Development

Created six KPI summaries using Excel PivotTables and the Data Model.

### Stage 3: Attendance Analysis

Built PivotTables to examine attendance status, monthly trends, departments, work modes, punctuality and leave categories.

### Stage 4: Data Visualisation

Converted the analytical PivotTables into charts designed to communicate attendance patterns clearly.

### Stage 5: Dashboard Development

Created a structured dashboard with KPI cards, charts, consistent formatting and navigation elements.

### Stage 6: Interactive Reporting

Connected compatible PivotTables to slicers and a date Timeline to allow dynamic filtering.

## Key Findings

### Overall Attendance

- 93.10% of attendance records were marked Present.
- Approximately 2.14% were Half Day records.
- Approximately 4.76% were On Leave records.

### Department-wise Attendance

Departmental present-record percentages were relatively close, generally falling within the low-to-mid 90% range.

### Monthly Attendance Trends

Present-record counts remained relatively stable across the three months, with March recording the highest number of Present entries.

### Leave Analysis

Casual Leave and Sick Leave were among the most frequently recorded leave categories.

### Late Arrivals

Average late-arrival minutes varied between departments, providing an additional perspective on employee punctuality.

These findings describe patterns in the dataset and should not be interpreted as evidence of employee performance or the causes of attendance differences.

## Dataset Source and Credits

This project uses the **Employee Attendance & Login Logout Data Bangalore** dataset published on Kaggle.

| Information | Details |
|---|---|
| Dataset | Employee Attendance & Login Logout Data Bangalore |
| Publisher | Satyaki Das |
| Kaggle Username | satyakidas07 |
| Reporting Period | January to March 2026 |
| Licence | CC0 1.0 Universal (Public Domain) |

**Original Dataset:**

[Employee Attendance & Login Logout Data Bangalore on Kaggle](https://www.kaggle.com/datasets/satyakidas07/employee-attendance-and-login-logout-data-bangalore)

**Dataset Publisher:**

[Satyaki Das on Kaggle](https://www.kaggle.com/satyakidas07)

### Acknowledgement

I would like to acknowledge Satyaki Das for publishing the dataset on Kaggle and making it publicly available.

The dataset was used for educational purposes and independent portfolio development.

The Excel-based data transformations, PivotTable analysis, KPI calculations, dashboard layout and interactive visualisations were independently developed as part of this project.

This project is not affiliated with or endorsed by the original dataset publisher.

## How to Use the Dashboard

1. Download the Excel workbook from this repository.
2. Open the file using Microsoft Excel for Windows.
3. Enable editing if prompted.
4. Navigate to the Dashboard worksheet.
5. Use the Attendance Date Timeline to select a month.
6. Apply the Department, Gender, Work Mode or Shift Type slicers to explore different groups.
7. Clear filters to return to the overall dashboard view.
8. Refresh the workbook if the underlying data source has been updated and is accessible.

Note: Some visualisations use specific attendance-status filters. Selecting a work mode may exclude leave records where work mode is recorded as Not Applicable.

## Project Limitations

- The analysis covers only January to March 2026.
- Findings reflect the supplied dataset and should not be generalised to an actual organisation.
- Present Rate is calculated from recorded attendance entries.
- Missing calendar dates are not automatically classified as absences.
- Attendance and working-hour measures do not directly measure employee productivity.
- Some filters may affect chart comparisons when certain categories have no applicable records.

## Future Enhancements

- Develop a monthly employee attendance tracker.
- Introduce employee-level attendance summaries.
- Add an employee search or selection feature.
- Expand the dashboard to additional reporting periods.
- Automate monthly HR attendance reports.
- Improve exception monitoring for attendance and punctuality.
- Explore integration with Power BI.

## Conclusion

This project demonstrates how Microsoft Excel can be used to clean, analyse and visualise employee attendance data through an interactive HR analytics dashboard.

It showcases practical experience in data preparation, PivotTable analysis, KPI reporting, dashboard development and interactive data visualisation.

The dashboard provides an accessible way to explore employee attendance patterns and supports data-driven HR reporting.

---

**Project Category:** HR Analytics | People Analytics | Excel Dashboard | Data Visualisation

**Tools Used:** Microsoft Excel, Power Query, PivotTables, PivotCharts, Slicers and Timeline
