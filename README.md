# Healthcare Data Analysis Dashboard

This repository contains the analysis and visualization of a healthcare dataset aimed at providing key insights into patient management, hospital operations, and financial trends. The project focuses on building an interactive dashboard using KPIs such as Admit Date, Discharge Date, Follow-up Date, and Billing Amount, along with visualizations to help healthcare professionals make data-driven decisions.

## Key Features

### KPIs:
- **Admit Date**: Date when the patient was admitted.
- **Discharge Date**: Date when the patient was discharged.
- **Follow-up Date**: Scheduled date for patient follow-up.
- **Billing Amount**: The total billing amount for each patient.
- **Health Insurance Amount**: Amount covered by health insurance.

### Visualizations:
1. **Bed Occupancy Analysis**: Track hospital bed occupancy to manage resources effectively.
2. **Feedback Volume per Doctor**: Analyze patient satisfaction across different doctors based on feedback.
3. **Diagnosis-wise Patient Count**: Get insights into the number of patients per diagnosis.
4. **Line Chart (Test vs Billing and Health Insurance Amount)**: A comparison of the billing amount and health insurance amount across different medical tests.

### Slicer:
- **Patient ID Slicer**: Filter data for individual patients to obtain more personalized insights.

## Technologies Used
- **Power BI**: For creating visualizations and interactive reports.
- **Python (Optional)**: For data preprocessing and analysis.
- **Pandas**: Data manipulation libraries.
- **Excel/CSV**: Data source.

## Installation and Usage

1. **Open the Power BI File**:  
   The `Healthcare_Dashboard.pbix` file contains the visualizations and can be opened using Power BI Desktop.

2. **Explore the Data**:  
   Use the dashboard slicers and interactive charts to explore patient data and gain insights.

## Dataset
The dataset used for this analysis contains the following columns:
- **Patient_ID**: Unique identifier for each patient.
- **Admit_Date**, **Discharge_Date**, **Followup_Date**: Dates related to patient admissions, discharges, and follow-ups.
- **Diagnosis**: The diagnosis provided to the patient.
- **Bed_Occupancy**: The status of bed occupancy.
- **Test**: Medical tests conducted.
- **Doctor**: The doctor responsible for the patient's care.
- **Feedback**: Patient feedback (scaled from 0 to 1).
- **Billing Amount**: The total bill for each patient.
- **Health Insurance Amount**: Amount covered by health insurance.
