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

### How is the district summary affected?
The passing_math_percentage equated to 74.8%, passing_reading_percentage equated to 85.7%, and overall_passing_percentage equated to 64.9% after recalculating with the new student count (excluding the ninth graders from Thomas High School). 
The original passing_math_percentage was 75.0%, passing_reading_percentage was 85.8%, and overall_passing_percentage was 65.2%. 
Comparing the originally calculated percentages that included the Thomas High School ninth graders to the new ones excluding the Thomas High School ninth graders, there is only a very small change. The new percentages are very slightly lower than the original ones. 

 ![districtsummary](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/1originalDistrictSummary.PNG)
 ***Image 1: Original District Summary***


 ![districtsummary1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/1DistrictSummary.PNG)
 ***Image 2: New District Summary***

### How is the school summary affected?

After calculating the passing percentages, looking solely at the 10th-12th graders' scores, it can be seen that the passing percentages (math, reading, and overall) all decreased very slightly after removing the ninth graders. 

The original passing math percentage was 93.3%, passing reading percentage was 97.3%, and overall passing percentage was 90.9% as seen below.

 ![schoolsummary](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/2origschoolsummarycropped.PNG)
 ***Image 3: Original School Summary***

Looking at only the tenth to twelvth graders, the new passing math percentage was 93.2%, passing reading percentage was 97.0%, and overall passing percentage was 90.6% as seen below.
![schoolsummary1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/2newschoolsummarycropped.PNG)
***Image 4: New School Summary***

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
With an overall passing percentage of 90.6% rather than the initial 90.9%, Thomas High School still remains as the second highest performing school.

![high1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/3originalhighschool.PNG)
***Image 5: Original Top Performing Schools***


![high1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/3newhighschool.PNG)
***Image 6: New Top Performing Schools***


### How does replacing the ninth-grade scores affect the following:

### Math and reading scores by grade
In the math and reading scores by grade, the ninth grade values for Thomas High School are replaced with NaN. In the original the math score was 83.6 and reading score was 83.7 for Thomas High School 9th Graders.

![mathscores](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/4origmathscoresbygrade.PNG)
![readscores](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/4origreadingscoresbygrade.PNG)

***Image 7: Original Math Scores by Grade (left) and Original Reading Scores by Grade (Right)***

![mathscores1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/4newmathscoresbygrade.PNG)
![readscores1](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/4newreadingscoresbygrade.PNG)

***Image 8: New Math Scores by Grade (left) and New Reading Scores by Grade (Right)***

### Scores by school spending
No significant change seen in the scores by school spending

![schoolspending](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/5newscoresbyschoolspending.PNG)
***Image 9: School Spending***

### Scores by school size
No significant change seen in the scores by school spending

![schoolsize](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/6newscoresbyschoolsize.PNG)
***Image 10: School Size***

### Scores by school type
No significant change seen in the scores by school spending

![schooltype](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/7scoresbyschooltype.PNG)
***Image 11: School Type***

## Summary
### Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- NaNs replaced the scores in the math and reading scores for ninth graders for Thomas High School as seen below
![nans](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/0NaN.PNG)

- The School summary metrics: passing math, passing reading, overall passing percentages were really low when calculating with the NaN's (before removing the ninth graders from the calculation) as shown below
![schoolsummary2](https://github.com/Soniaprogram/School_District_Analysis/blob/main/Images/8%20originalschoolsummarycropped.PNG)
