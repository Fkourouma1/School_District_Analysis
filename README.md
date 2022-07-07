# School_District_Analysis
## Overview of the school district analysis
This project goal is to help Maria, the chief data scientist for a City Schools District, analyze data on students funding and test score as well as school data. We will be visualizing the School District Data Summary without the reading and math grades for Thomas High School ninth grades. Finally, we will be helping out visualize the District Data Summary final result. 
## Results Using bulleted lists and images of DataFrames as support, address the following questions
### How is the district summary affected? student count
### How is the school summary affected?
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
### How does replacing the ninth-grade scores affect the following:
        - Math and reading scores by grade
                - Math score: the original average math score was 78.98%
        - Scores by school spending: after refactoring, the school spending did not changed()see image attached)
        - Scores by school size: regarding the school size summary, we did not notice any change(see image attached)
        - Scores by school type: the school type summary were not impact by the ninth grades alteration. 
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

district summary original, 
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	39,170	$24,649,428.00	79.0	81.9	75	86	65

refactored 
Total Schools	Total Students	Total Budget	Average Math Score	Average Reading Score	% Passing Math	% Passing Reading	% Overall Passing
0	15	38,709	$24,649,428.00	78.9	81.9	74.8	85.7	64.9

overall passing percentage in the original is 65.17232575950983 but 64.85571830840374
overall passing math and reading  count is 25528 but
print(passing_math_percentage) 74.9808526933878 but 74.76039164018704
print(passing_reading_percentage) 85.80546336482001 but 85.6596657108166
new student count 38709 , student count 39,170
average_math_score 78.98537145774827

average_reading_score 81.87784018381414

total_budget 24649428 original but
9th grade for THS 461

THS_student_count Student ID    1174
THS_passing_math_count 1094

THS_math_reading_passing_count 1064

district_summary_df["Total Budget"]  $24,649,428.00
