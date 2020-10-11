# School District Analysis
 
## Overview and Purpose
The previous data analysis on our school and student data was discovered to be based on faulty data. The numbers recorded for Thomas High School ninth graders is questionable due to a cheating problem. To resolve our data analysis we will perform the same operations on the dataset(s) but exclude the numbers related to Thomas High School ninth grade class using the Python Pandas module
## Results
The original district summary yielded the following results. displayed in the image below.
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/original_data.png?raw=True)
- Total Schools:  15
- Total Students: 39,170
- Total Budget:   $24,649,428.00
- Average Math Score: 79.0
- Average Reading Score: 81.9
- % Passing Math : 75
- % Passing Reading: 86
- % Overall Passing: 65
 
The Image below displays our data after removing the Thomas High School ninth grade values
 
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/final_dataset.PNG?raw=True)
- Total Schools:  15
- Total Students: 38,709
- Total Budget:   $24,649,428.00
- Average Math Score: 78.9
- Average Reading Score: 81.9
- % Passing Math : 74.8
- % Passing Reading: 85.7
- % Overall Passing: 64.9
 
With the cheating scores removed, Average Math score dropped from 79.0 to 78.9 while Average reading scores remained virtually unchanged. We can also see
a decrease in the following categories:% Passing Math which dropped from 75 to 74.8, % Passing Reading from 86 to 85.7, and  % Overall Passing from 65 to 64.9. Almost all categories had dropped in averages.
 

The school summary is mostly identical, but after removing the questionable data we can see a drop in decimal places for all items in the Thomas High School columns pertaining to scores and score averages
 
Below is the original results followed by the new outcome:
 
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/old_per_school.png?raw=True)
 
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/new_per_school.png?raw=True)
 
 
### Old
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/original_Thomas_scores.png?raw=True)
 
### New
![alt text](https://github.com/sebcampos/School_District_Analysis/blob/main/resources/new_Thomas_scores.png?raw=True)
 
In the above images we are viewing the school data relevant to Thomas high school. When comparing the old and new datasets we can see that all the values pertaining to scores and score averages have dropped while total students and other columns that are unrelated where not changed.
 

- Math and reading scores by grade
  - These scores and averages have dropped
- Scores by school spending
  - These values have remained the same
- Scores by school size
  - These values have remained the same
- Scores by school type
  - These values have remained the same
 
## Summary
 
After replacing the reading and math scores we saw a new dataset which applied the functions of averaging and counting these scores to the new dataset. This data set was then used to create the per school dataset. This was all done without changing the budgets, total students, and total school budgets, and school type in the original dataset. This created a final data set reflecting the most accurate scores while maintaining the integrity of the original dataset
