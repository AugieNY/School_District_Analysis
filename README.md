# School_District_Analysis

## Overview:
We are assisting the Chief data scientist for a city school district. The main objective is to analyze the dataset based on every student math and reading scores, as well as the school infomation they attend. We are aiming to showcase trends in school performance and their students.

## Analysis & Findings
After some data cleaning and organizing the missing values (with python and panda documentation), data types, we were able to narrow down the analysis and our findings. There are 15 schools in the school district and 13,940 students. The school with the most students is Montgomery High School when Chang High School as the least student.

The average reading score is almost similar between school types (.17 difference) when the math score is greater in Charter Schools (+3.81). The 9th grade being the mean of the grade column, we should use that value to compare all schools, students, and school types.

## Furthermore, additional Analysis
It would be great to add more variable and deeper analysis in order to provide a more accurate picture and reality of the city district. I would start the deep dive via:

### (1) Top Schools
Comparing the number of students per school and the average score in reading and maths. We should be able to set a variable per school with a weight of number of students compare to the average score in both domains (reading and maths).

### (2) Top Students
It would also be interesting to look at the top 10 students in each school and overall of all schools. Which school is most represented in the top 50 students (avg combined score of math and reading by student). We could argue, no matter the findings, that Montgomery has the most chance (in %) to have more better student but we would need the number to validate this hypothesis. In the same manner, we should count the % of students in Charter Schools vs Public ones.

### (3) Best performing grades in each school
It would be interested to rank grades in each school from the most performing to the least performing.

Aside from schools we can also perform the analysis of (1), (2), and (3) with the school type.
