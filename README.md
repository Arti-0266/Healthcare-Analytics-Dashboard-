# Healthcare Analytics Dashboard

## Overview
This Power BI dashboard provides detailed insights into healthcare services, focusing on patient wait lists, case types (Day Case, Inpatient, Outpatient), and specialties. It enables users to analyse healthcare performance across various dimensions such as time periods, specialties, and patient demographics.

## Key Features

### Summary

1. KPIs:
  - Latest Month Wait List: Total patients on the wait list for the latest 
     month.
  - Previous Year (PY) Latest Month Wait List: Comparison with the previous       year's data.
  - Key Indicators (Average/Median): Includes metrics like average wait list 
     times for specialties such as:
      - Accident and Emergency
      - Pediatric Cardiology
      - Pediatric Orthopedic Surgery

2. Visualizations:
 - Wait List by Case Type: A pie chart showing the proportion of 
     Outpatient, Day Case, and Inpatient cases.
 - Wait List by Time Bands and Age Profile: A bar chart displaying wait 
     list distribution across time bands (e.g., 0-3 months, 3-6 months) and       age groups (0-15, 16-64, 65+).
 - Trends Over Time:
       - Total cases by type (Day Case, Inpatient) from 2018 to 2021.
       - Sum of totals by year, month, and case type.

3. Interactive Filters:
 - Date Range: Custom date selection.
 - Case Type: Drill down into specific case types.
 - Specialty Name: Explore data by medical specialties.
  
  ### Detailed View
  
 1.	Interactive Filters:
    - Date Range: Adjust the time frame of analysis.
    - Case Type: Filter by Day Case, Inpatient, or Outpatient.
    - Specialty Name: Select specific medical specialties.
    - Age Profile: Analyse data by patient age groups.
    - Time Bands: View data by specific time intervals.

2.	Table Insights:
    - Aggregated data for each specialty by year and quarter.
    - Breakdown of total cases into Day Case, Inpatient, Outpatient, and           cumulative totals.
    - Easy comparison across specialties and periods.

## Data Source
- Folder Structure:
  - The Dataset is oranized in two folders:
    - Inpatient : Contains csv files for inpatient data.
    - Outpatient : Contains Excel files for outpatient data.
  - File Format: All data files are in csv file format.
     [Download link](https://github.com/Arti-0266/Healthcare-Analytics-Dashboard-/tree/main/Healthcare%20Data)

## Data Insights
 - Trends: Track patient wait lists, service utilization, and trends across     years (2018-2021).
 - Specialties: Identify high-performing or high-demand specialties.
 - Wait Times: Analyse patient wait times by case type, time band, and age      profile.

## Prerequisites
 - Software: Power BI Desktop or Power BI Service for viewing and 
   interacting with the dashboard.
   [Download link](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
 - Data Preparation:
     - Place the Inpatient and Outpatient folders in the same directory as 
       the Power BI file.
     - Update the data source paths in Power BI to reflect the correct file 
       locations.
       [Download link](https://github.com/Arti-0266/Healthcare-Analytics-Dashboard-/blob/main/Health%20care%20DB.pbix)


## How to Use
1.	Clone or download the repository.
2.	Open the Power BI (Health care DB.pbix) file in Power BI Desktop.
3.	Ensure data source folders are correctly linked (Healthcare Data).
4.	Navigate between the "Summary" (Sheet 1) and "Detailed View" (Sheet 2)       for different analyses.
5.	Use interactive filters to refine data views and gain specific insights.

## Screenshot of Summary:
   <img width="638" alt="Healthcare sheet1" src="https://github.com/user-attachments/assets/6ec1cd17-bc5d-42a0-b2ff-70dedc01b281" />

## Detailed View:
  <img width="638" alt="healthcare sheet 2" src="https://github.com/user-attachments/assets/9a8837d9-40b3-4802-ba9e-e9c6b1f35f57" />


## Potential Use Cases
 - Hospital administrators can monitor and optimize patient flow and 
   resource allocation.
 - Policy makers can use the data to evaluate healthcare system performance.
 - Researchers can identify trends and gaps in healthcare delivery.


## Future Enhancements
 - Add more visualizations such as scatter plots or heat maps for deeper 
   insights.
 - Include geographic analysis by integrating location data.
 - Enhance predictive analytics capabilities for forecasting patient wait 
   lists and case trends.
