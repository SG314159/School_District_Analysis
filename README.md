# Module 4 Assignment - PyCitySchools

Challenge 4 for UT Bootcamp.

Focus: Use Python and the Pandas library to analyze ficticious school district data and showcase trends in school performance.


## Overview of School District Analysis
The module exercises outlined the analysis of school and student performance for the math and reading tests. The analysis for the Challenge was to adjust the original analysis to not include the Thomas High School 9th graders. Per Challenge 4 instructions, the 9th grade math and reading scores were changed to NaN values and the analysis was redone. 

The original data set included scores for 39,170 students. The data set without THS 9th graders had 38,709. The difference of 461 students is 1.1% of the original data set.

## Results
This section compares the test results for the original data (all students) and the revised data set (without scores for THS 9th).
- District Summary: The average math score for the district was slightly lower, at 78.9 down from 79.0. The average reading score for the district was the same (to one decimal place of precision) at 81.9. The percentages for each of these were also nearly identical to the entire data set (without THS 9th).

- School Summary: The scores for all the schools other than Thomas High School were identical between the two data sets since THS was the only school with changes. Only the row with Thomas High School changed in the values for Average Math Score (down from 83.41 to 83.35), Average Reading Score (up from 83.85 to 83.90), Percent Passing Math (down from 93.3% to 93.2%), Percent Passing Reading (down from 97.3% to 97.0%), and Overall Passing Percent (down from 90.9% to 90.6%). These changes are negligible due to the small number of students. The Per Student Budget stayed the same because it was not recalculated without THS 9th.

- Thomas High School: The revised data set did not affect the ranking of Thomas High School relative to other schools. With the original data set, THS ranked second by Overall Percentage. Cabrera High School had the highest overall passing percentage of 91.33%, and Griffin High School ranked third after THS with an overall passing percentage of 90.59%. The overall passing percentage for THS was 90.9% with the original data set and 90.6% with the revised data set. In both cases, THS ranks second. 

- Math and Reading Scores by Grade: The only change to the tables showing by-grade comparisons is that the cell for 9th grade at Thomas High School is NaN instead of the corresponding values. All other schools remain the same, and the 10th-12th grade values for THS are the same between the two data sets. 

- Spending and Scores by School: Thomas High School is in the same spending bracket ($630-644/student) for both data sets. The average math scores for this spending bracket differ only 0.02 between the entire data set and the revised data set. The average reading scores also differ by only 0.02. Thus, it is fair to say that there is not a noticeable difference between the scores when grouped by spending.

- Size and Scores by School: Thomas High School is in the same size bracket (Medium) for both data sets. The final tables grouped by size have the same math and reading scores for both data sets. Thus, it appears there is no difference between the scores when grouped by size. This is likely due to the fact that only 461 scores were replaced in the revised data set and it is a small percentage (1.1%) of the overall scores. It also means that the Grade 9 THS scores were not drastically different from other scores in the same size bracket.

- Type and Scores by School: Thomas High School is in the same type bracket (Charter) for both data sets. The final tables grouped by school type have the same math and reading scores for both data sets. Thus, it appears there is no difference between the scores when grouped by school type. As with the size grouping, this is likely due to the fact that only 461 scores were replaced in the revised data set and it is a small percentage (1.1%) of the overall scores. It also means that the Grade 9 THS scores were not drastically different from other scores in the same school type bracket.


## Summary
The revised data set with THS 9th grade removed did not yield drastically different results than the original data set. The percent passing for math, reading, and overall each went down but only by a minute 0.3%. District passing percentages were essentially the same. 

The THS 9th grade scores that were removed for the revised data did not change the overall picture drastically. Thus, the scores were relatively similar to other scores and groups across the district. Any concern about the validity or integrity of the THS 9th grade scores and possible academic misconduct should be made solely on the basis of those scores and the situation involved. The validity or integrity of those scores cannot be confirmed or denied via any affect or lack thereof on the district analysis.