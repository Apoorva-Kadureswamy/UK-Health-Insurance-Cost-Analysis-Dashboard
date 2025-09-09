# UK-Health-Insurance-Cost-Analysis-Dashboard
## Overview

This Power BI dashboard explores the impact of demographic and lifestyle factors on health insurance costs in the UK. It provides interactive insights using a dataset of 2,200 individuals, helping to identify cost drivers such as smoking, age, exercise, BMI, and more.

## Dataset Used
- <a href="https://github.com/Apoorva-Kadureswamy/UK-Health-Insurance-Cost-Analysis-Dashboard/blob/main/uk_health_insurance_dataset.csv">Data set</a>


## 🎯 Business Questions / KPIs

1. What is the average insurance cost overall?                
2. How do charges differ between smokers and non-smokers?     
3. What is the effect of diet and exercise on insurance cost? 
4. How does age and BMI correlate with charges?               
5. Are there regional differences in insurance cost?          
6. How do number of children affect insurance costs?          
7. What is the distribution of income vs charges?             

## Process

### Step 1: Data Preparation

* Cleaned and validated data in Power BI
* Created calculated columns like `IncomeBand`, `AgeGroup`, and `Region_Location`

### Step 2: Data Modeling

* No relationships required (flat table)
* Measures and calculated columns created in DAX:

  * `Total Smokers`, `Average Charges`, `Average BMI`, etc.

### Step 3: Dashboard Design

* Created KPIs using Card visuals
* Used Bar, Column, Stacked, and Scatter Charts
* Added region-based map with corrected geocoding
* Applied filters for dynamic analysis


## Dashboard Screenshots
![Screenshot of Dashboard 1](https://github.com/Apoorva-Kadureswamy/UK-Health-Insurance-Cost-Analysis-Dashboard/blob/main/Dashboard.jpg)


## Key Insights

* **Smokers pay 3x more** on average than non-smokers.
* **Low exercise and poor diet** increase insurance costs, especially for smokers.
* **Charges increase with age**, especially after 50.
* **BMI shows moderate correlation** with cost, but less than age or smoking.
* **Regional differences** in charges exist, with Northern Ireland and South East showing variation.
* **Families with more children** tend to have slightly higher charges.


## Skills Demonstrated

* Power BI Dashboard Design
* Data Modeling & DAX
* Data Cleaning & Transformation
* Insight Generation & Storytelling
* Data Visualization Best Practices




