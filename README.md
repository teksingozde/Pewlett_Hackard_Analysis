# Pewlett Hackard Analysis

## Project Overview

The Pewlett Hackard Company is requesting a study of its own employee database of people who will retire soon. In this study, it will be determined who will retire in which departments and which positions should be suspended.

### Resources

Datasets:

- departments.csv
- dept_emp.csv
- dept_manager.csv
- employees.csv
- salaries.csv
- titles.csv

Other Sources:

- pgAdmin 4 
- PostgreSQL 15.0

## Overview of the Analysis

The datasets given to us for this analysis are shown in the Datasets folder, the written SQL code work is in the "Employee_Database_Challenge.sql" and the datasets of the new tables that we have created using the datasets given to us in the study are shown in the "Datasets" folder.
The data sets we want to create;

- current_emp.csv
- mentorship_eligibilty.csv
- retirement_info.csv
- retirement_title.csv
- retiring_titles.csv
- unique_titles.csv

The outputs of these datasets are in the "Outputs" folder, with the first 12 lines being displayed.

## Results

Tables obtained as a result of SQL outputs are shown below.

#### Table 1. Current Employee
<img width="452" alt="Screen Shot 2022-10-27 at 6 47 32 PM" src="https://user-images.githubusercontent.com/26927158/198418085-ebc0a83c-90b8-4fe3-ae90-6884d961e64c.png">

#### Table 2. Mentorship Eligibility
<img width="733" alt="Screen Shot 2022-10-27 at 6 34 30 PM" src="https://user-images.githubusercontent.com/26927158/198417836-c5752d76-48e4-4215-8c93-bc9df19f0926.png">

#### Table 3. Retirement Info
<img width="372" alt="Screen Shot 2022-10-27 at 6 34 46 PM" src="https://user-images.githubusercontent.com/26927158/198417495-77c87270-cc8b-4384-8a4f-b1da9ef6dd76.png">

#### Table 4. Retirement Titles 
<img width="372" alt="Screen Shot 2022-10-27 at 6 34 46 PM" src="https://user-images.githubusercontent.com/26927158/198417872-e930de55-0d37-4275-b0bb-b55700d0787e.png">

#### Table 5. Retiring Titles 
<img width="249" alt="Screen Shot 2022-10-27 at 6 35 20 PM" src="https://user-images.githubusercontent.com/26927158/198417910-d9748020-dec3-435e-b693-55ccbd0083ca.png">

#### Table 6. Unique Titles 
<img width="496" alt="Screen Shot 2022-10-27 at 6 35 36 PM" src="https://user-images.githubusercontent.com/26927158/198417944-89f05fe1-c96d-4e94-a99e-0c0988a3eebc.png">

- The fact that there are two managers who are expected to retire indicates the low number of managers in general. The retirement of even two executives means a huge potential loss for the company. Because less manager means more responsibility of every manager.

- The Company includes 25,916 Senior Engineers and 24,926 Senior Personnel, who are expected to retire. These numbers are very high, and so many people suddenly retiring will mean that business is often disrupted. For this, promotion policies need to be rearranged and new jobs must be purchased.

- When necessary analyzes are made for mentoring; Senior Engineers work as Engineers, Technical Leaders and Senior Staff, and they are usually in pretty good positions. However, if they are new, their potential to mentor in scholars and promotion situations is also high.

## Summary

- Three departments with an average desk of over $50,000 are Finance, Marketing and Sales. Employees in the Development, Human Resources, Production and Customer service departments earn an average salary of $40,000.

- The number of people who will retire is much higher than the number of mentors who can potentially take part in the company. If these people decide to leave the company due to their low wages, it will mean a high rate of employee and job loss for this company. Realizing that salaries are so low, mentors may wish to remain mentors. In order to avoid these situations, it is necessary to make arrangements in salaries at regular intervals.






