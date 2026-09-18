# Student Performance Data Quality Project

## Project Overview

I created this project as a practical challenge to apply the data analysis concepts I had learned so far.

Instead of completing several disconnected exercises, I created a small student-performance dataset and approached it like a junior data analyst receiving data that needed to be investigated before analysis.

The main question was:

> Can this dataset be trusted enough to investigate whether attendance is related to test performance?

---

## Objective

The objectives of this project were to:

- Inspect the quality of the dataset
- Identify data quality problems
- Clean the data
- Validate the cleaned data
- Analyse the relationship between attendance and test performance
- Visualise the relationship
- Communicate the findings clearly

---

## Dataset

The dataset contains student-level records with the following variables:

- Student ID
- Age
- Study Hours
- Attendance
- Test Score
- Study Method

The dataset was created for learning and practice purposes.

---

## Data Quality Issues Identified

During the data audit, I identified:

- A duplicate student record: S009
- A missing Study Hours value for S011
- A missing Age value for S017
- An invalid Attendance value of 110% for S012

---

## Data Cleaning

The following actions were taken:

- Removed the duplicate S009 record from the working dataset.
- Kept the missing Study Hours value for S011 blank rather than inventing a value.
- Kept the missing Age value for S017 blank rather than inventing a value.
- Removed the invalid 110% attendance value for S012 by leaving it blank.
- Preserved the original dataset separately as Raw Data.

---

## Analysis

After cleaning and validation, I investigated the relationship between attendance and test scores.

### Results

- Average Attendance among valid attendance records: **83.63%**
- Average Test Score among valid attendance–test score pairs: **74.79**
- Correlation between Attendance and Test Score: **0.9761**

The correlation indicates a very strong positive relationship between attendance and test scores in this dataset.

The scatter plot also shows an upward pattern, with higher attendance generally corresponding to higher test scores.

---

## Visualization

A scatter plot was used to visualise the relationship between:

- X-axis: Attendance (%)
- Y-axis: Test Score

A scatter plot was selected because the analysis focused on the relationship between two numerical variables.

---

## Key Findings

1. The original dataset contained several data quality issues that needed to be addressed before analysis.

2. After cleaning and validation, the valid attendance records had an average attendance of **83.63%**.

3. Attendance and test scores showed a very strong positive relationship, with a correlation of **0.9761** in this dataset.

---

## Limitation

This is a small, practice dataset and the analysis is observational.

Therefore, the strong relationship observed does **not** prove that higher attendance causes higher test scores.

Other factors may also influence student performance.

---

## Workflow

The project followed this workflow:

**Data Audit → Data Cleaning → Data Validation → Analysis → Visualization → Interpretation**

---

## Tools Used

- Google Sheets
- GitHub

---

## What I Learned

This project helped me understand that data analysis does not begin with creating charts or calculating averages.

Before analysing data, I need to understand the dataset, check its quality, identify problems, clean it carefully, and validate the result.

The biggest lesson from this project was:

> **Good analysis starts before the analysis.**

---

## Project Status

Completed as a beginner data analysis practice project.
