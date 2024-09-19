# PATIENT ELECTRONIC HOSPITAL RECORDS ANALYSIS

### Dashboard snapshot link: ![image](https://github.com/user-attachments/assets/a88c89c4-c251-4d88-ac80-45b39e5d4e36)

## Problem Statement:
Hospitals encounter significant difficulties in managing patient admissions efficiently due to varying factors such as patient age, medical conditions, and admission urgency. 
These challenges are compounded by inconsistent patterns in admissions, high billing costs, and complex insurance processes. The lack of clear insight into how these variables interact 
leads to overcrowding, delayed treatments, and suboptimal resource use.
This project focuses on analyzing hospital patient admission data to optimize resource allocation, reduce emergency admissions, and streamline billing processes. 
The dataset includes patient demographics, medical conditions, admission types, and financial details, providing insights to improve hospital operations and patient care.

## Data:
The dataset consists of patient demographic details, medical conditions, admission dates, discharge dates, billing amounts, and insurance information. 
It covers a wide range of variables such as age, gender, blood type, and medications.

## Tools Used:
### 1. MS Excel: 
Likely used for data cleaning, basic analysis, and creating summary tables.
### 2. Power BI: 
Used for visualizing data, creating the dashboard, and displaying key insights like trends, distributions, and performance metrics.

## Key Features and KPIs:
### 1. Number of Patients: 
10K

### 2. Total Admissions: 
10K

### 3. Total Billing Amount: 
255M

### 4. Average Billing Amount per Patient: 
26K

### 5. Average Age: 
51 Years

### 6. Total Hospitals: 
8640

### 7. Blood Group Distribution: 
Visualization showing the different blood groups (A-, A+, B-, etc.) for the patients.

### 8. Gender Distribution: 
50.75% Male vs. 49.25% Female

### 9. Admission Type: 
32.42% Urgent, 33.67% Emergency, and 33.91% Elective

### 10. Most Common Medical Conditions:
Conditions such as Cancer, Hypertension, and Diabetes are highlighted as the most common diagnoses among the admitted patients.

### 11. Most Recommended Medications:
Medications like Penicillin, Lipitor, Ibuprofen, Aspirin, Paracetamol are frequently prescribed.

### 12. Insurance Provider Distribution:
Shows the number of patients covered by different insurance providers, including Cigna, Blue Cross, Aetna, United, and Medicare.

### 13. Trends in Admissions Over Time (Month):
A line graph showing monthly trends in patient admissions, with the highest admissions in October (883) and the lowest in February (778).

### 14. Trends in Admissions Over Time (Year):
Annual admissions from 2018 to 2023, peaking in 2022 at 2.1K admissions, with a drop in 2023 to 1.6K.

### 15. Trends in Admissions Over Time (Quarter):
A line chart showing quarterly trends in patient admissions, with a significant spike in Q4 with 2.5K admissions.

## Solution Development (SD):
### 1. Predictive Analytics for Admission Management
The trends in admissions over time show monthly and yearly fluctuations, with peaks in certain months (e.g., October) and specific quarters (Q4). 
There is also a notable distribution of urgent, emergency, and elective admissions
### SD: 
Develop a Predictive Model: Build a predictive analytics solution that uses historical data to forecast future patient admissions. 
By analyzing past admission trends, hospitals can predict periods of high inflow (e.g., Q4 or October) and plan resources (e.g., beds, staff, equipment) accordingly.

### 2. Optimized Resource Allocation Based on Admission Types
The distribution of admission types (Urgent: 32.42%, Emergency: 33.67%, Elective: 33.91%) reveals a balanced mix, 
but emergencies require immediate attention and resources, which can strain hospital facilities if not managed efficiently.
### SD: 
Build an Admission Prioritization Tool: Develop a system that categorizes patient admissions based on urgency and automates resource allocation (e.g., ICU beds, emergency staff) accordingly. 
This tool can dynamically adjust staffing and resource levels based on real-time admissions data, ensuring critical patients receive immediate attention.

