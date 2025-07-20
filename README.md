# 🧍‍♂️🧬 Health Analysis – BMI Trends by Generation

## Overview

This project explores **Body Mass Index (BMI)** trends across different generational cohorts using health and demographic data. The main objective was to understand how BMI varies by generation and uncover patterns related to age, gender, and health risk.

The entire analysis was done using **Power BI** with data preparation handled in **Power Query**, enabling dynamic filtering and visualization.

---

## Objectives

- Calculate and analyze BMI across various age groups and generations.
- Compare average BMI and obesity rates across generational cohorts.
- Visualize BMI distribution and health risk categories (underweight, normal, overweight, obese).
- Build an interactive dashboard for easy exploration and presentation of insights.

---

## Tools Used

- **Power BI Desktop**
  - Interactive visualizations and slicers
  - DAX measures and calculated columns
- **Power Query**
  - Data cleaning and transformation
  - Custom column creation and data type handling

---

## Dataset

Key fields used:

- `Age`
- `Birth Year`
- `Gender`
- `Height (m)` and `Weight (kg)`
- `BMI` (calculated as `Weight / (Height^2)`)

*Generational labels were assigned based on the birth year.*

---

## Analysis Workflow

### 1. Data Cleaning (Power Query)

- Removed rows with missing or implausible height/weight values.
- Calculated **BMI** for each individual using a custom column formula.
- Added a **Generation column** by categorizing birth years into generational buckets.
- Filtered out BMI outliers using conditional logic.

### 2. Data Modeling & Measures (DAX)

- Created measures for:
  - Average BMI per generation
  - % of population by BMI category
  - Gender-specific BMI averages
- Built relationships and hierarchies for smooth slicing/filtering.

### 3. Dashboard Development (Power BI)

The dashboard includes:

- **Line Chart** of average BMI by generation
- **Bar Charts** showing BMI category breakdowns by gender
- **Slicers** for Generation, Gender, and BMI Category
- **KPI Cards** for overall average BMI and obesity rate

![Dashboard](https://github.com/EmmanuelKiriinya/Health-Analysis-PowerBI-/blob/master/image/Health%20Dashboard.PNG)

---

## Key Insights

- **Millennials and Gen X** had the highest average BMI, with obesity rates above 30%.
- **Gen Z** showed lower average BMI but rising overweight trends in early adulthood.
- Gender differences were notable — males had higher BMI on average across all cohorts.
- The data suggests a growing public health concern among working-age generations.

---

## Conclusion

BMI trends show clear generational differences, with Millennials and Gen X at higher health risk due to overweight and obesity. These findings highlight the need for targeted health interventions, particularly for high-risk age groups.

---

## Next Steps

- Integrate additional lifestyle data (e.g., exercise, diet, screen time) if available.
- Extend the dashboard to include regional analysis or longitudinal trends.
- Deploy the Power BI report as a web-based or mobile-accessible dashboard.

---

## Author

**Emmanuel Kiriinya**  
Data Analyst | Power BI • Excel • SQL • Python  
[GitHub](https://github.com/EmmanuelKiriinya) | [Email](mailto:emmanuelkiriinya1@yahoo.com)
