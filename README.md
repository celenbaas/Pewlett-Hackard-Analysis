# Pewlett-Hackard-Analysis

## Overview
This analysis first looks at the number of retiring employees by job title and second the employees that are eligible for the mentorship program.

## Results

![image](https://user-images.githubusercontent.com/96347024/154580182-b396dfa4-7f35-4f15-9d57-e9b3fe960324.png)

o Senior Engineers have the highest number of employees retiring with 25,916, which makes up 36% of the Total Retirements.

o Senior Staff have the second highest number of employees retiring with 24,926 which makes up 34% of the Total Retirements.

o Overall senior level employees make up 70% of the retirements.

![image](https://user-images.githubusercontent.com/96347024/154580471-ced0faae-484a-452f-ab30-a82067c866ab.png)


o There are 1,549 employees eligible for mentorship.  There are 569 Senior Staff level and 529 are Senior Engineer.


## Summary
o	How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are 72,458 employees with birthdays between January 1, 1952 and December 31, 1955 that are considered eligible for retirement.

o	Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
There are 1,549 employees born between January 1, 1965 and December 31, 1965 who are qualified to mentor the next generation.  The Counts and percentage breakout by job title can be seen below.  The senior level positions make up 71% of the mentors available.

![image](https://user-images.githubusercontent.com/96347024/154584540-a0c25741-bd10-4f77-b41d-048aac5c9362.png)

Below are two additional data points that could be further analyzed:

(1) Using the membership eligibility csv I have calculated each employees Years of Service by taking todays date – from date and divided that by 365.  This tells me that the longest people have worked is 37 years.  Here is a sample:
![image](https://user-images.githubusercontent.com/96347024/154597230-3ad319a6-53fa-4ea1-a10c-9bec52c85419.png)

(2) If after further review leadership decides more mentors are needed one option to expand the mentorship eligibility would be to look at those born between 1960 and 1966.  This adjustment would be made within the where clause using the following code: e.birth_date BETWEEN '1960-01-01' AND '1966-12-31'
