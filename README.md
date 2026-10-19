# Bellabeat Fitness Tracker Analysis

## Project Overview

This project explores Fitbit fitness tracker data to identify daily activity patterns and develop marketing recommendations for Bellabeat. The analysis focuses on the Bellabeat Time watch and considers how smart-device usage trends could help Bellabeat understand and engage its customers.

This is a practice case study completed as part of my data analytics learning journey.

## Business Task

Analyse smart device usage data to identify trends in daily steps, active minutes, and sedentary time, then use the findings to suggest potential marketing strategies for Bellabeat.

## Tools Used

- Google Sheets
- Spreadsheet formulas
- Pivot tables
- Data cleaning
- Data visualisation

## Dataset

- **Dataset:** Fitbit Fitness Tracker Data
- **File analysed:** `dailyActivity_merged.csv`
- **Source:** Mobius, via Kaggle
- **Data period:** April–May 2016
- **Licence:** CC0, as stated in the Coursera case study instructions

The dataset contains daily activity records including steps, distance, calories burned, active minutes, and sedentary minutes.

## Data Cleaning

The dataset was checked for missing values, duplicate user-date records, inconsistent date formats, and negative values. Activity dates were converted into a proper date format. Zero-step records were investigated and retained because it was unclear whether they represented inactivity or the device not being worn.

## Analysis

Using Google Sheets, I calculated summary statistics and compared average daily steps and sedentary minutes across the days of the week. I also analysed average minutes spent at different activity levels and created charts to communicate the findings.

## Key Findings

- **Highest average daily steps:** Saturday, approximately 8,153 steps.
- **Lowest average daily steps:** Sunday, approximately 6,933 steps.
- **Difference:** Approximately 1,220 steps between Saturday and Sunday.
- **Highest average sedentary time:** Monday, approximately 1,028 minutes.
- **Lowest average sedentary time:** Thursday, approximately 962 minutes.
- The activity-level analysis showed substantially more sedentary and lightly active minutes than very active and fairly active minutes.

## Recommendations

Based on the observed patterns, the analysis suggests that Bellabeat could explore:

1. Encouraging daily movement through activity-tracking features.
2. Promoting regular movement breaks.
3. Encouraging personal activity goals and progress tracking.

These are potential strategies to investigate, rather than proven outcomes.

## Limitations

The dataset is historical and represents Fitbit users rather than Bellabeat customers. The sample is limited, and the findings may not represent all consumers. Further research would be needed to confirm whether these patterns apply to Bellabeat's target audience.

## Project Report

See the full PDF report in this repository for the data-cleaning process, visualisations, findings, and recommendations.

## Author

Data Analytics Portfolio Project

