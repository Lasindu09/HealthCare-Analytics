# Healthcare Analytics Dashboard

## Overview

This dashboard provides a comprehensive analysis of patient wait lists and case distributions in a healthcare setting. It includes key metrics, trends, and visualizations to help stakeholders monitor and 
understand patient flow and case types over time.

## Features
### 1.Key Metrics:
- Latest Month Wait List: Displays the total number of patients on the waitlist for the most recent month.
- PY Latest Month Wait List: A comparison metric showing the previous year's waitlist for the same month.
![Screenshot 2024-12-16 193301](https://github.com/user-attachments/assets/e59e6cd2-e23e-406a-957f-0c656d25ac8a)
### 2.Case Type Split:
- Breakdown of case types:
   - Outpatient
   - Day Case
   - Inpatient
- Percentage contribution and absolute numbers are provided.

![02](https://github.com/user-attachments/assets/30d76adc-6841-4ced-b4a6-9340fac2f64a)

### 3.Time Band vs Age Analysis:
- Wait time distribution categorized by time bands (e.g., 0-3 months, 3-6 months).
- Age profile analysis to identify patient demographics.

![03](https://github.com/user-attachments/assets/820adf28-cbc8-4896-994d-89657584e4f9)
### 4.Top 5 Specialties:
- Identifies the specialties with the highest patient volumes, such as Pain Relief and Pediatric Respiratory Medicine.

![04](https://github.com/user-attachments/assets/480fe579-9a1f-427f-8149-0088f748da09)
### 5.Monthly Trend Analysis:
- Trends in the patient wait list over time, with distinctions between Day Case/Inpatient and Outpatient cases.
- Displays seasonal or periodic patterns in patient volumes.

![05](https://github.com/user-attachments/assets/5992dda1-5814-4bcb-83fb-575b12298543)
### 6.Summary View:
- Total patient numbers categorized by case type and monthly trends.
- Clear visualization of key indicators and comparisons over the years.

![06](https://github.com/user-attachments/assets/4666c259-060f-4276-b3f4-6d75c481a32b)


## Data Sources
- Archive Date Range: January 31, 2018 – March 31, 2021.
- Fields analyzed:
   - Archive_Date
   - Case_Type (Day Case, Inpatient, Outpatient)
   - Specialty_Name
   - Age_Profile
   - Time_Bands
   - Total

## Usage Instructions

### 1.Navigation:
- Use slicers to filter data by Case_Type, Specialty_Name, Age_Profile, or specific Archive_Date.
- Drill down into visualizations for more detailed insights.
### 2.Comparative Analysis:
- Use the Latest Month Wait List and PY Latest Month Wait List to assess year-over-year changes.
- Analyze trends to optimize resource allocation and patient care.
### 3.Insights on Patient Flow:
- Examine Time Band vs Age and Top Specialties to identify bottlenecks and high-demand areas.
