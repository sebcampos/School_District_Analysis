# School District Analysis

## Overview and Purpose
The previous data analysis on our school and student data was discovered to be based on faulty data. The numbers recorded for Thomas High School ninth graders is questionable due to a cheating problem. To resolve our data analysis we will perform the same operations on the dataset(s) but exclude the numbers related to Thomas High School ninth grade class using the Python Pandas module
## Results

- how is the district summary affected 
 
  The original district summary yeilded the following results. displayed in the image below.
  
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

With the cheating scores removed, Average Math score dropped from X to Y while Average reading scores remained the same. We can also see
a decrease in the following categories:% Passing Math, % Passing Reading, and  % Overall Passing

- how is the school summary affected



- how does replacing the ninth graders' math and reading scores affect Thomas High School's performance
- How does replacing the ninth-grade scores affect the following
    - Math and reading scores by grade
    - Scores by school spending
    - scores by school size
    - scores by school type

## Summary

Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.