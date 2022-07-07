# School_District_Analysis
## Overview of the school district analysis
This project goal is to help Maria, the chief data scientist for a City Schools District, analyze data on students funding and test score as well as school data. We will be visualizing the School District Data Summary without the reading and math grades for Thomas High School ninth grades. Finally, we will be helping out visualize the District Data Summary final result. 
## Results 
### How is the district summary affected?
The district summary was affected by the change of the student count which previously 39,170 and now after the removal of the 9th graders in Thomas High School, the new count count was 38,709; the math average score as well as the reading average score were also impacted. We will see the details below. 
### How is the school summary affected? 
The school summary(for Thomas High School) was affected by looking at the average math and reading score(images are attached). In the original code, the passing was percentage was 93.27 % while the refactored shows 93.18 %. The passing reading percentage shows in the original code as 97.31% while it was down in the refactored code as 97.02 %. and the overall passing percentage was 90.95% in the original code but 90.63% in the refactored one. 
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools? 
Removal of the 9th graders math and reading score impacted the average math score for Thomas High School which was 83.42 in the original script but was  lower in the refactored code as 83.35. For the average reading score, it was 83.85 in the original while 83.90 in the refactoried code. For the overall passing percentage in the original script, it was 65.17 while it was 64.86 in the second code.
### How does replacing the ninth-grade scores affect the following:
        - Math and reading scores by grade
                - Math score: For the 9th graders, Thomas High School shows 83.59 for the math score in the original script, while we replace it by Nan the refactored code. The 10th graders math score was 83.09, 11th graders was 83,50  and the 12th was 83.50 for both original and refactored code.
                - Reading score: the 9 th graders for THS was 83.73 But NaN in the refactored code. The 10th, 11th and 12th graders were not impacted as their reading score was 84.25, 83.59, and 83.83.
        - Scores by school spending: after refactoring, the school spending did not changed()see image attached)
        - Scores by school size: regarding the school size summary, we did not notice any change(see image attached)
        - Scores by school type: the school type summary were not impact by the ninth grades alteration. 
## Summary
In the school summary for the top schools, the average math score for Thomas High School was 83.42 in the original script but was  lower in the refactored code as 83.35. For the average reading score, it was 83.85 in the original while 83.90 in the refactoried code. For the overall passing percentage in the original script, it was 65.17 while it was 64.86 in the second code. The passing math percentage was 74.98 but in the second script, it was  74.76. The passing reading percentage show 85.81 in the first code while 85.66 in the refactored code. 
The 9th graders count for Thomas High School was 461 which we subtracted from the total student count 39,170 and gave a total of 38,709 students. 
