# Student Performance Analysis

## Overview
An exploratory data analysis of 395 secondary school students examining how **study habits** and **absences** impact academic performance. Built as a portfolio project combining domain knowledge from math teaching with data analysis skills.

## Questions Explored
1. **Does study time actually improve student performance?**
2. **Do absences affect student performance?**

## Key Findings
- Students who study **5-10 hours/week** score the highest on average (11.4/20), about 1.4 points above those who study less than 2 hours.
- Studying **more than 10 hours** doesn't guarantee better results — possibly because struggling students compensate with extra effort. However, this group is small (27 students), so the finding should be interpreted cautiously.
- There is a clear **negative relationship between absences and grades**: students with low absences (0-3) average 12.3, while those with very high absences (16+) average 10.0.
- A critical data cleaning step was needed: **38 students scored 0 on G3** (likely dropouts), which initially distorted the absence analysis.

## Tools Used
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook

## Dataset
UCI Student Performance Dataset — Math course from two Portuguese secondary schools.
- 395 students, 33 features
- Grades scored on a 0-20 scale across three periods (G1, G2, G3)
