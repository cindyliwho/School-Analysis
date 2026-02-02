# PyCitySchools Analysis (Education Data Analytics)

## Overview
This project analyzes school district data to evaluate **academic performance trends** across multiple schools. Using Python and Pandas, the analysis compares student outcomes based on **school size, budget, and school type** (district vs charter) to uncover patterns in math and reading achievement.

The goal is to provide data-driven insights that can inform education policy and resource allocation.

---

## Dataset
The analysis uses two datasets:
- **Schools data** – school name, type, size, and budget
- **Student data** – student scores, grade levels, and school assignments

These datasets are merged and analyzed to generate district-wide and school-level summaries.

---

## Technologies Used
- **Python**
- **Pandas**
- **NumPy**
- **Jupyter Notebook**

Key libraries:
- `pandas`
- `numpy`

---

## Analysis Workflow

### 1) District Summary
Calculates high-level metrics across the entire district, including:
- Total number of schools and students
- Total budget
- Average math and reading scores
- Percentage of students passing math, reading, and overall

---

### 2) School Summary
Generates per-school performance metrics:
- Total students
- School budget and per-student budget
- Average math and reading scores
- Passing percentages

---

### 3) Top & Bottom Performing Schools
- Identifies the **highest-performing** and **lowest-performing** schools based on overall passing rate
- Highlights performance differences across schools

---

### 4) Performance by Grade
Breaks down average math and reading scores by:
- Grade level (9th–12th)
- School

---

### 5) Performance by Spending, Size, and Type
Analyzes how academic outcomes vary by:
- **Spending per student**
- **School size** (small, medium, large)
- **School type** (charter vs district)

---

## Key Findings
- Charter schools generally outperform district schools in overall passing rates
- Higher spending per student does **not** necessarily correlate with higher academic performance
- Smaller and medium-sized schools tend to have higher passing rates than larger schools

---

## Key Concepts Demonstrated
- Data cleaning and merging
- Groupby aggregations
- Educational performance metrics
- Comparative data analysis
- Translating data into actionable insights
