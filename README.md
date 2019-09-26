# sat-act-analysis
Analyse trends in SAT &amp; ACT data from 2017 - 2018

# Project 1: SAT & ACT Analysis

## Problem Statement

Analyse trends in SAT & ACT data from 2017 - 2018 and make recommendations to increase SAT participation and scores.

## Executive Summary

### Contents:
- 2017 Data Import & Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

## Data Dictionary (2018 data is named the same other than the year)

|Feature|Type|Dataset|Description|
|---|---|---|---|
|*Column Name*|*int/float/object*|*ACT/SAT*|*Description of each column*| 
|sat_17_state|*object*|SAT|The name of each of the 51 states in USA|
|sat_17_participation|*float*|SAT|The proportion of students tested *(0.5 represents 50% of students in state)*|
|sat_17_erw|*int*|SAT|Avg. SAT Subtest (Evidence-Based Reading and Writing) score for each state *(max. of 800 and min. of 200)*|
|sat_17_math|*int*|SAT|Avg. SAT Subtest (Math) score for each state *(max. of 800 and min. of 200)*|
|sat_17_total|*int*|SAT|Avg. Total SAT Test score for each state *(max. of 1600 and min. of 400)*|
|act_17_state|*object*|ACT|The name of each of the 51 states in USA|
|act_17_participation|*float*|ACT|The proportion of students tested *(0.5 represents 50% of students in state)*|
|act_17_english|*float*|ACT|Avg. ACT English score for each state *(max. of 36 and min. of 1)* |
|act_17_math|*float*|ACT|Avg. ACT Math score for each state *(max. of 36 and min. of 1)*|
|act_17_reading|*float*|ACT|Avg. ACT Reading score for each state *(max. of 36 and min. of 1)*|
|act_17_science|*float*|ACT|Avg. ACT Science score for each state *(max. of 36 and min. of 1)*|
|act_17composite|*float*|ACT|Avg. ACT Composite score max. for each state *(max. of 36 and min. of 1)*|



### Sources:
- [1st ACT 2018 Dataset](https://magoosh.com/hs/act/2016/average-act-score-by-state/)
- [2nd ACT 2018 Datset](https://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf)
- [SAT to ACT Conversion Table](https://collegereadiness.collegeboard.org/pdf/guide-2018-act-sat-concordance.pdf)
- [ACT & SAT Scores and Percentiles](https://blog.prepscholar.com/sat-math-vs-act-math-whats-the-difference)

### Conclusions:  

- Based on the findings found in the 2017 & 2018 data, and after some analysis, it is amazing to see how the news confirms the data findings, i.e. that there is indeed a negative relationship between performance & participation.

- It would have been useful to find other data sources to do more complex analysis, such as demographics data and how that can affect over all State test scores.






