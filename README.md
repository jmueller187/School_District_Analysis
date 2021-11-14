# School_District_Analysis

## Overview of the school district analysis: 
The purpose of the this analysis was to evaluate and summarize student funding and student standardized test scores for 15 schools with over 39,000 students in a local school district. We were asked to aggregate the data, and identify trends in school performance across ths district to assist with decision making on schuul budgets and priorities.
Once this analysis was complete, it was discovered that there was evidence of academic dishonesty among the math and reading grades for the 9th grade students at Thomas High School. In an effort to uphond the testing standards set by the state, we were asked to remove the math and reading scores for the Thomas High School 9th graders, and replace them with NaN values and repeat the full district analysis with the remaining data intact

## Analysis Results:

### How was the district summary affected?
- After repeating the district summary with the Thomas High Shcool 9th grade test scores removed, it was discovered that the overall results were not significantly affected. Removing the 9th graders data affected the results by less than 1 percentage point. You have to remove the rounding formatting from the data to see where the changes occur.

![Original Spending Analysis Data](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/DistrictAnalysisOrigjData.png)

![Adjusted Spending Analysis Data](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/DistrictAnalysisAdjData.png)

### How was the school summary affected?
- Again, simalar to the district summary, the overal school summary results were impacted by less than one percentage point as illustrated by the following data frames:

![Original School Summary Data](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/SchoolSummaryOrigData.png)

![Adjsted School Summary Data](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/SchoolSummaryAdjData.png)

### How did replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
- When comparing the results with the other schools, we saw that the math and reading scores for Thomas High School were affected signifcantly, moving from an overall passing percentage of 65% with all grades included to 91% with the 9th grade scores removed. This moved Thomas High School from one of the lower performing schools to the second highest performing school.

![Passing percentages with all students included](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/ThomasHSAllStudents.png)

![Passing percentages with Thomas High School 9th grade removed](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/ThomasHS9thGradeRemoved.png)

![Top 5 Performing Schools](https://github.com/jmueller187/School_District_Analysis/blob/main/Resources/Top5PerformingSchools.png)

### How does replacing the ninth grade scores affect the following:
- Math and Reading Scores by Grade: This was the most significant change to the district results. Thomas High School moved to the second highest performing school by removing the 9th grade math and reading test scores.
- Scores by School Spending: No significant change to the overall district results.
- Scores by School Size: No significant change to the overall district results.
- Scores by School Type: No significatt change to the overall district results.

## Summary: 
Here are the to three most striking changes to the school district analysis after replacing the reading and math scores for the ninth grade at Thomas High School with NaN:
1. Removing the 9th grade scores changed the overall passing percentage for Thomas High School by 26 percentage ponts, from 65% to 91%.
2. When the scores for approximately 400 students from one school were removed from the data set, we a less than one percentage point change in the overall district results based on shcool spending, school size or school type.
3. The request to remove the 9th grade scores at Thomas High School required signifiacnt time to recompile the school data for for the remaining three grades. Once the school data revisions were complete, we were able to reuse the remainder of our original code to repeat the school analysis.
