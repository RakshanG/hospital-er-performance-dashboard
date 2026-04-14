# hospital-er-performance-dashboard
Analysis of 9K+ hospital emergency room visits to uncover wait time patterns, department performance, and patient satisfaction trends using Tableau.

# Overview 
An analysis of 9,000+ emergency room patient records to identify patterns in wait times, department performance, patient volume, and satisfaction scores. The goal is to surface actionable insights that a hospital administrator could use to improve staffing, reduce wait times, and enhance patient experience.

# https://public.tableau.com/authoring/HospitalERPerformanceDashboard/HospitalERPerformanceDashboard#1
<img width="1199" height="805" alt="Screenshot 2026-04-14 at 12 53 13 AM" src="https://github.com/user-attachments/assets/7d6036a7-7c3a-47d0-9813-af994d2e9ffc" />

# Key Findings

1. Wait times peak between 11 AM – 1 PM, suggesting the ER is most strained during late morning and early afternoon. Late night hours see the shortest waits. This points to a clear staffing optimization opportunity — shifting resources toward midday coverage.

2. Neurology has the longest average wait time, followed by Physiotherapy and Gastroenterology. Renal and General Practice have the shortest. Specialist departments appear bottlenecked, likely due to fewer available physicians.

3. Patient satisfaction does not strongly correlate with wait time. Patients gave the full range of satisfaction scores (0–10) regardless of whether they waited 10 minutes or 60 minutes. This suggests other factors — bedside manner, communication, outcome — may drive satisfaction more than wait duration alone.

4. Monday is the busiest day for ER visits, while Friday sees the lowest volume. Weekend volume picks back up on Saturday. A hospital could reallocate staffing from Friday to Monday to better match demand.

# Data Source

Hospital Emergency Room Dataset
Source: Kaggle — Hospital Emergency Room Dataset
Records: ~9,000+ patient visits
Fields used: date, patient_id, wait_time, satisfaction_score, department_referral, gender, age, race

# Tools Used

Tableau Public — Dashboard creation and interactive visualization

# Dashboard Components
ChartWhat It ShowsWait Time by HourLine chart showing average wait time across 24 hours of the dayWait Time by DepartmentHorizontal bar chart comparing average wait by department referralSatisfaction vs Wait TimeScatter plot exploring relationship between wait duration and patient satisfactionVolume by DayLine chart showing patient count by day of the week
All charts are interactive — clicking a department filters every other chart to show data for that department only.

# How to Reproduce

Download the dataset from Kaggle
Open Tableau Public (free) and connect to the CSV file
Build four worksheets: wait time by hour (line), wait time by department (bar), satisfaction vs wait time (scatter), volume by day (line)
Combine into a single dashboard and enable filter actions

# What I'd Do Next - 

Segment wait times by patient age group to see if elderly patients wait longer
Analyze whether gender or race correlates with wait time or satisfaction — important for identifying potential equity gaps
Build a heat map of hour × day of week to find the exact worst times to visit the ER
Add a predictive model to forecast daily patient volume and recommend staffing levels

# About
Built as part of a data analyst portfolio project. The goal was to demonstrate healthcare data analysis, dashboard design, and the ability to extract operational insights that could improve hospital performance.
