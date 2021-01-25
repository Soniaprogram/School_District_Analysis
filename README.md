# School_District_Analysis


## Overview of the school district analysis
Maria, a chief data scientist for a city school district, is responsible for analyzing standardized test scores, preparing all test data for analysis, reporting, and presenting performance trends and patterns. The insights garnered through this analysis will influence discussions and strategic decision making at the school and district level. 

I will be assisting Maria in analyzing student funding and student standardized test scores. With the math and reading scores for each student, along with, school data provided to me, I will aggregate the data and showcase trends in school performance. This analysis will in turn assist the school principal and superintendent make decisions in regards to the school's budget and priorities. I will be using the Pandas Python library along with Jupyter Notebook to inspect the data and perform my analysis. 
Due to evidence of academic dishonesty, specifically reading and math grades for Thomas High School ninth graders, these scores will have to be nulled while keeping the rest of the data intact. This project will go over the analysis changes due to removing these grades. 

Deliverable 1: Replace ninth-grade reading and math scores at Thomas High School

Deliverable 2: Repeat the school district analysis. Recreating the following metrics: 
- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type)

## Results

#### How is the district summary affected?
The passing_math_percentage equated to 74.8%, passing_reading_percentage equated to 85.7%, and overall_passing_percentage equated to 64.9% after recalculating with the new student count (excluding the ninth graders from Thomas High School). 
The original passing_math_percentage was 75.0%, passing_reading_percentage was 85.8%, and overall_passing_percentage was 65.2%. 
Comparing the originally calculated percentages that included the Thomas High School ninth graders to the new ones excluding the Thomas High School ninth graders, there is only a very small change. The new percentages are very slightly lower than the original ones. 

*Insert picture of district summary

#### How is the school summary affected?

After calculating the passing percentages, looking solely at the 10th-12th graders' scores, it can be seen that the passing percentages (math, reading, and overall) all decreased very slightly after removing the ninth graders. 

The original passing math percentage was 93.3%, passing reading percentage was 97.3%, and overall passing percentage was 90.9% as seen below.

*insert

Looking at only the tenth to twelvth graders, the new passing math percentage was 93.2%, passing reading percentage was 97.0%, and overall passing percentage was 90.6% as seen below.

*insert

#### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
With an overall passing percentage of 90.6% rather than the initial 90.9%, Thomas High School still remains as the second highest performing school.

#### How does replacing the ninth-grade scores affect the following:

##### Math and reading scores by grade
No change seen in the math and 

##### Scores by school spending
No change seen in the scores by school spending

*insert

##### Scores by school size
No change seen in the scores by school spending

*insert

##### Scores by school type
No change seen in the scores by school spending

*insert

## Summary
### Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
