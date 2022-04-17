# Pewlett-Hackard-Analysis

## Overview of the analysis: Explain the purpose of this analysis.
The data we were required to pull consisted of creating tables and importing CSV files and exporting new data based on employee information provided for us by Bobby. Bobby has asked us figure out two things: the number of retiring employees per title and to identify employees who eligilible to participate in a mentorship program. After we extract this data, we need to analyze the data to determine the size of the "silver tsunami" (i.e., number of people retiring) in order to better prepare his company for upcoming changes in staffing.

## Results: Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

- From an overview with our first table (retirement_titles), there are 133,776 employees about to retire. Once we filter the this table, however, and drop any duplicates to the table, the number drops to 72,458 employees about to retire. This shows approximately 60,000 of these employees either moved departments or were promoted to another role, which are the duplicates in the data.
- Looking at the retiring_titles table, we can see the largest title impacted by employees retiring is the Senior Engineer title followed by Senior Staff with almost the same amount of employees retiring. The smallest title impacted by this factor is Manager.
![retiring_titles.png](Images/retiring_titles.png)
- 

## Summary: Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."
##### How many roles will need to be filled as the "silver tsunami" begins to make an impact? 
According to the retiring title table, there are 72,458 employees retiring leading to that amount of roles needing to be filled.  
##### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
When we view the retiring_titles tables side by side with a mentorship count, it becomes clear that there are not enough emplyoees qualified to fill these roles immediately. Doing a comparison, there are not nearly enough employees who are qualified for a Senior Engineer role; this is important to point out considering the amount of Senior Engineers retiring from this role. The one title that may appear to have a chance for filling in the gaps in employement is the Staff role. 

![retiring_titles.png](Images/retiring_titles.png) ![mentorship_count.png](Images/mentorship_count.png)
