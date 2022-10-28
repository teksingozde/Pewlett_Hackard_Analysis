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

The outputs of these datasets are in the "Outputs" folder, with the first 14 rows being displayed.

## Results

Tables obtained as a result of SQL outputs are shown below.

#### Table 1. Current Employees
<img width="452" alt="Screen Shot 2022-10-27 at 6 47 32 PM" src="https://user-images.githubusercontent.com/26927158/198418085-ebc0a83c-90b8-4fe3-ae90-6884d961e64c.png">

Above is the current employee table. The first 14 rows of each table are included. In the table, the number of the employee, first name and last name and the year they will work are included. The fact that the dates in all of them are 9999-01-01 is due to the fact that the dates they will retire and leave the job are not certain.

#### Table 2. Mentorship Eligibility
<img width="733" alt="Screen Shot 2022-10-27 at 6 34 30 PM" src="https://user-images.githubusercontent.com/26927158/198417836-c5752d76-48e4-4215-8c93-bc9df19f0926.png">

In the mentorship eligibility table, candidates who are eligible for mentorship are shown. The employee number, first name, last name, date of birth, the date they started, the date their employment will end, and the title information of these people are included. Looking at the table, it can be clearly said that there are generally senior employees and that titles such as senior engineer, engineer, technical leader, assistant engineer, staff are mostly in the top 14 positions.

#### Table 3. Retirement Information
<img width="372" alt="Screen Shot 2022-10-27 at 6 34 46 PM" src="https://user-images.githubusercontent.com/26927158/198417495-77c87270-cc8b-4384-8a4f-b1da9ef6dd76.png">

Table 3 is included as the retirement information table. In this table, a study of people who have the potential to retire is made. Looking at the table, employee number, first name and last name information are included.

#### Table 4. Retirement Titles 
<img width="664" alt="Screen Shot 2022-10-27 at 7 06 07 PM" src="https://user-images.githubusercontent.com/26927158/198419790-facb3d62-3854-4c16-bdb1-c18d6c7c98e7.png">

The table above is similar to table 3, and in table 3, the titles and dates of employees working in positions suitable for retirement can be seen from the first time they started. On the other hand, it can be clearly observed what titles these people had from the moment they first started until the moment they were promoted, and what ages and titles were generally in a position to retire.

#### Table 5. Retiring Titles 
<img width="249" alt="Screen Shot 2022-10-27 at 6 35 20 PM" src="https://user-images.githubusercontent.com/26927158/198417910-d9748020-dec3-435e-b693-55ccbd0083ca.png">

Table 4 is in the form of retirement titles, and as seen in the table, these titles are mostly found in Senior Engineer and Senior Staff titles. It is also noteworthy that 2 people are in the title of manager. It is a separate issue with the scarcity of employees with managerial titles and the accumulation of senior engineers and senior staff employees in terms of titles.

#### Table 6. Unique Titles 
<img width="496" alt="Screen Shot 2022-10-27 at 6 35 36 PM" src="https://user-images.githubusercontent.com/26927158/198417944-89f05fe1-c96d-4e94-a99e-0c0988a3eebc.png">


- The fact that there are two managers who are expected to retire indicates the low number of managers in general. The retirement of even two executives means a huge potential loss for the company. Because less manager means more responsibility of every manager.

- The Company includes 25,916 Senior Engineers and 24,926 Senior Personnel, who are expected to retire. These numbers are very high, and so many people suddenly retiring will mean that business is often disrupted. For this, promotion policies need to be rearranged and new jobs must be purchased.

- When necessary analyzes are made for mentoring; Senior Engineers work as Engineers, Technical Leaders and Senior Staff, and they are usually in pretty good positions. However, if they are new, their potential to mentor in scholars and promotion situations is also high.

## Summary

- Three departments with an average desk of over $50,000 are Finance, Marketing and Sales. Employees in the Development, Human Resources, Production and Customer service departments earn an average salary of $40,000.

- The number of people who will retire is much higher than the number of mentors who can potentially take part in the company. If these people decide to leave the company due to their low wages, it will mean a high rate of employee and job loss for this company. Realizing that salaries are so low, mentors may wish to remain mentors. In order to avoid these situations, it is necessary to make arrangements in salaries at regular intervals.






