# Pupil-Register

## Introduction
The *Pupil Register* explores student enrollment data across 128 academies, focusing on class distribution, stream allocation, and learning status of over 7,500 pupils. Using Power BI, the dataset was cleaned, modeled, and visualized to uncover key insights into academic engagement, dropout trends, and grade-level performance. The goal is to support school administrators with a data-driven overview of enrollment patterns and pupil status, enabling more informed planning and decision-making.

![](https://github.com/Esther-git87/Pupil-Register/blob/main/enrollment%20picture.jpg)

## Problem Statement
School administrators across 128 academies need clear visibility into student enrollment patterns, grade-level distributions, and the current learning status of pupils. Manual registers provide limited insights, making it difficult to monitor trends in class participation, withdrawals, and graduation. This dashboard offers a centralized data-driven solution for tracking key student metrics and informing decisions.

## Dataset Overview

![](https://github.com/Esther-git87/Pupil-Register/blob/main/register%20data.png)

The dataset contains a school register of 7,539 pupils across 17 grades and 128 academies, including key details such as:
Grade Name (e.g., Primary 1–7, Baby Class)

- Academy Name

- Stream (A–H)

- Student Status (Allowed in Class, Not Allowed, Withdrawn, Graduated)

- Data was cleaned, modeled, and visualized in Power BI.


## Tools & Techniques Used

 The following features were incorparated:
 
- Power BI: Data cleaning, modeling, and visualization

- Power Query: Data transformation and value standardization (e.g., fixing inconsistent grade names)

- DAX: Measures for status percentages and filters (e.g., Student Count, Graduated %, Top N Academies)

- Tooltips,

- Button,

- Page navigation

## Modelling
---

The Model comprise of a single table.

![](https://github.com/Esther-git87/Pupil-Register/blob/main/register%20modelling.png)

 
 ## Dashboard Pages Summary
 
 ## Enrollment Distribution

 ![](https://github.com/Esther-git87/Pupil-Register/blob/main/register%201.png)

### Key Visuals and Insights

#### Total KPIs:

- Pupils: 7,539

- Academies: 128

- Grades: 17

### Key Insight

- A few academies handle a large portion of the student population.

- Enrollment gradually reduces as grades increase — possibly due to dropouts or graduation.

- Baby and middle classes show healthy early enrollment trends.


### Status/Stream Analysis

![](https://github.com/Esther-git87/Pupil-Register/blob/main/register%202.png)

### Key Insight

- High number of withdrawals could indicate systemic issues in early education.

- Some streams are overpopulated while others are underused.

- Tracking Graduated students from Primary 7 confirms data integrity.



## Recommendations
- Investigate high withdrawal rates, especially in early primary grades.


- Balance stream distribution to optimize learning environments.


- Provide targeted support to students in lower grades with higher dropout risks.


- Use trends to plan infrastructure and teacher deployment per academy.


