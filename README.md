# Military Training Analytics and Decision Support System

**Tools:** Microsoft Excel (VBA) | Microsoft Power BI  
**Author:** Kings Mwandira  
**Status:** Complete and Deployable

---

## Overview

This project builds a complete end-to-end training analytics system for military recruits and officer cadets. It replaces manual paper-based reporting with an automated system that captures scores, calculates performance, and displays results on an interactive dashboard.

---

## The Problem

Military training units collect large amounts of performance data every day. In most cases this data is written by hand and stored in files without being properly analysed. This leads to:

- No real-time visibility of trainee performance
- Delayed identification of struggling trainees
- No easy way to compare companies
- Best instructors not recognised based on data

---

## The Solution

A four-layer automated system:

| Layer | Tool | Function |
|-------|------|----------|
| Data Entry | Excel + VBA | Structured form with Submit button |
| Data Storage | Excel Table | Named table tbl_training |
| Processing | VBA + Power Query | Auto score calculation |
| Visualisation | Power BI | Interactive 2-page dashboard |

---

## Training Courses

**Recruits (6 courses)**
- Weapons, Field Craft, Tactics, Map Reading, Medical, Physical Training

**Officer Cadets (9 courses)**
- All 6 Recruit courses plus Jungle Survival, Issuing of Orders, Service Writing

---

## Companies

| Type | Companies |
|------|-----------|
| Recruits | A Coy, B Coy, C Coy, D Coy, E Coy, F Coy, G Coy, H Coy |
| Officer Cadets | A Coy, B Coy, C Coy, D Coy |

---

## System Features

- Login system with Admin and Basic User access levels
- VBA Submit button saves records automatically
- Smart duplicate detection-same Number + Course updates existing record
- New course entries insert directly below existing trainee rows
- Average Score calculated across all course rows per trainee
- Performance Level assigned automatically-Excellent / Competent / Needs Improvement
- Validation prevents Recruits from entering Cadet-only scores
- Validation prevents Cadets from being assigned Recruit-only companies

---

## Dashboard -Page 1: Training Performance

![Recruits Dashboard]|Confidential)
![Cadets Dashboard]|Confidential)

---

## Dashboard -Page 2: Company Performance

![Company Recruits]|Confidential)
![Company Cadets]|Confidential)

---

## Performance Levels

| Level | Score |
|-------|-------|
| Excellent | 80 and above |
| Competent | 60 to 79 |
| Needs Improvement | Below 60 |

---

## How to Use

1. Open TrainingData.xlsm
2. Login with your credentials
3. Fill in the DataEntry form and click Submit
4. Save the Excel file
5. Open Dashboard.pbix in Power BI Desktop
6. Click Refresh
7. Dashboard updates automatically

---

## Related Projects

- [Malawi Banking Credit Risk Analytics](https://github.com/mwandirakings-prog/malawi-banking-analytics)

---

## Author

**Kings Mwandira**  
Data Analyst | Business Intelligence Analyst   
mwandirakings@email.com
