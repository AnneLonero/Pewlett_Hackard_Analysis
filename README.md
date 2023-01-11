# Pewlett_Hackard_Analysis

Pewlett Hackard is a large company boasting several thousand employees and begining to see employees retiring at a rapid rate. Pewlett Hackard is looking to create an analysis to identify those who are retiring to prepare retirement package and hiring need in the near future.

## Overview

This analysis was created using SQL to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program.

## Results

After runninng queries to determind number of employees retiring per title, we found the result below.

![retiring count per title](https://user-images.githubusercontent.com/114631804/211874405-f2140df0-1179-4a28-91cf-4c291249cdf5.png)

Senior Engenering and Senior Staff by far have the biggest numbers of retiring employees compare to other titles. 

However, there are only two managers were indetified who are retiring.

According to requirement, only employees who were born in 1965 eligible for mentorship program. Therefore, we found 1550 employees who met this criteria. 

This eligible employees are only 2.1% of the total expected retiring number.

## Summary

There are total of 72,458 postions will need to be filled as employees start retiring. 

According to the analysis, there is not enough qualified, retirement-ready employees to mentor the next generation of Pewlett Hackard as you can see in below table.

![eligible emplyee count per title](https://user-images.githubusercontent.com/114631804/211875924-670c5c98-19fa-4837-aaa5-83e210c4643e.png)


There are few question we can ask to clarify more needed information. For example, in the table above, we ran a query to group the eligible employee by titles so that we can identify our resources and need more easily. Using query:

![image](https://user-images.githubusercontent.com/114631804/211878051-31353fe7-f6f4-40c7-9c6d-28621564906d.png)

We can also expand the eligibility to another years, for example 1964, to accomodate the mentorship program, and provide more resources for new empployees, especially for Manager position. While we have 2 manager positions will be available, with the eligibility limited, we don't have any resource available for mentorship program, but we get at least 1 person after expanding our criteria. And just by expanded this criteria for one more year, the possible available resosurces is average 16 times more for all titles as you can see below.

![eligibble employee count expanded](https://user-images.githubusercontent.com/114631804/211876558-15fdd78e-c5c8-4054-a046-097a9047392c.png)

Query used for this expanded criteria

![expand criteria query](https://user-images.githubusercontent.com/114631804/211878470-91cdcb63-0b76-48bb-82e4-11fccc2729fd.png)

The analysis is an evolving process and can be utilized to explore more potential need and accommodation for an organizational operation in the future.
