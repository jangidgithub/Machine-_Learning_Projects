# tabular-minicap-1
Repository for data and code for minicap-1 project

## Problem Description

Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problem your client is facing is around identifying the right people for promotion (only for manager position and below) and prepare them in time. Currently the process, they are following is:

They first identify a set of employees based on recommendations/ past performance
Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion
For above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle.

![](img.jpg)

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

## Variable	Definition

1. employee_id	- Unique ID for employee
2. department - Department of employee
3. region - Region of employment (unordered)
4. education	- Education Level
5. gender - Gender of Employee
6. recruitment_channel - Channel of recruitment for employee
7. no_of_trainings - no of other trainings completed in previous year on soft skills, technical skills etc.
8. age - Age of Employee
9. previous_year_rating - Employee Rating for the previous year
10. length_of_service - Length of service in years
11. KPIs_met >80% - if Percent of KPIs(Key performance Indicators) >80% then 1 else 0
12. awards_won?	- if awards won during previous year then 1 else 0
13. avg_training_score - Average score in current training evaluations
14. is_promoted	(Target) - Recommended for promotion

## Evaluation Metric

The evaluation metric for this competition is F1 Score.

## Expected Outcome

1. Predictions on test.csv in sample_submission.csv format.
2. An EDA report with your findings in the dataset (can be any format html, pdf, docx etc. but not jupyter notebooks)
3. List of top 5 important features

