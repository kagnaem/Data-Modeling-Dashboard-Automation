# Donor Behavior Analysis and Forecasting for a Not-for-Profit Organization

## Project Overview
This repository presents a donor analytics project designed for a not-for-profit organization. The project combines data pipeline design, data modelling, dashboard development, donor segmentation, and forecasting to support better fundraising decisions and donor engagement strategies.

The work brings together Microsoft Fabric, Power BI, DAX, Python, and external data sources to transform donor data into a decision-support reporting solution.

## Project Objective
The aim of this project is to:
- analyse donor behaviour over time
- segment donors based on engagement and giving patterns
- build dashboards for donor reporting and drill-down analysis
- map donor locations with external property and boundary data
- forecast future donations using multiple forecasting methods

## Tools and Technologies
- Microsoft Fabric
- Power BI
- DAX
- Python
- Prophet
- Matplotlib
- LINZ boundary data
- OneRoof property data

## What the Project Covers

### 1. Data Pipeline and ELT Workflow
The project includes an ELT-style data pipeline built in Microsoft Fabric within the Microsoft 365 environment. Data is loaded, cleaned, transformed, and structured before being used for modelling and reporting.

### 2. Data Modelling and Dashboarding
Power BI Desktop is used to connect to the prepared data, build calculated tables and DAX measures, and create interactive dashboards for donor analysis.

### 3. Donor Behaviour Analysis
The dashboards analyse donor contributions across five fiscal years and classify donors into categories such as:
- new
- increasing
- decreasing
- retained
- lapsed

This helps identify donor trends and changes in giving behaviour over time.

### 4. Donor Mapping
The project integrates donor records with external geospatial and property data to create an interactive donor map across New Zealand. This allows users to explore donor information alongside average property values by location.

### 5. RFM Analysis
The solution includes RFM segmentation to analyse:
- Recency
- Frequency
- Monetary value

This supports donor targeting by identifying the most engaged and valuable supporters.

### 6. Forecasting and Model Comparison
The project compares multiple forecasting methods for future donation analysis, including:
- Average forecasting
- Linear Regression
- Prophet

The presentation concludes that Prophet is the most effective approach for this use case because of its flexibility, interpretability, and ability to handle business-style time series patterns.

### 7. Donor and Segment-Level Forecasting
The final dashboards allow drill-down forecasting at both donor-group and individual-donor level, improving practical usability for fundraising teams.

## Main Project File
- [DATA INSIGHTS-NOT FOR PROFIT ORGANIZATION.pdf](./DATA%20INSIGHTS-NOT%20FOR%20PROFIT%20ORGANIZATION.pdf)

This PDF is the main project deliverable and documents the methodology, dashboards, data pipeline, segmentation logic, forecasting approach, and reporting outputs.

## Confidentiality Note
This project is based on a real not-for-profit analytics engagement. Some organization-specific details, figures, and sensitive information have been anonymized, blurred, or intentionally omitted to protect privacy and confidentiality while still demonstrating the technical workflow and business value of the project.

## Why This Repository Fits Data Modeling, Dashboard, and Automation
This project belongs in this repository because it combines three core themes:

- **Data Modeling**: building structured reporting tables, calculated measures, and donor segmentation logic
- **Dashboarding**: creating interactive donor, behavioural, and geographic reports in Power BI
- **Automation and Workflow**: using Microsoft Fabric and ELT processes to prepare large datasets efficiently for reporting

## Business Value
This project shows how data can help a not-for-profit organization:
- understand donor behaviour more clearly
- identify valuable donor groups
- target fundraising efforts more effectively
- forecast donation trends
- support decision-making with interactive dashboards

## Suggested Future Improvements
- Add dashboard screenshots to the repository for faster GitHub preview
- Add a short architecture diagram or data flow image from the presentation
- Add sample DAX measures or a short methodology note in Markdown
- Add a companion `INSIGHTS_REPORT.md` summarising the main findings from the PDF

## Summary
This repository contains a practical end-to-end donor analytics project that demonstrates data pipeline design, Power BI modelling, dashboard development, donor segmentation, and donation forecasting in a not-for-profit context.
