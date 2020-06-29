# School_District_Analysis
Analysis for school districts for week 4. Done with Python and Anaconda
# Challenge Analysis
The following text corresponds to the questions that need to be answered in a written report for the PyCitySchools Challenge (Module 4)

---
### How is the District Summary Affected?
When we removed the 9th grade math and reading scores for Thomas High School in the challenge notebook, there was an observed decrease in multiple metrics that were described in the district summary DataFrame.

1. The Average Math Score decreased by 1.1 points from 79.0 to 78.9.
2. The Average Reading Score stayed the same at 81.9
3. The % passing math decreased by 1% from 75% to 74%
4. The % passing reading decreased by 2% from 86% down to 84%
5. The Overall passing % decreased by 1% from 65% down to 64%

As a result, I conclude that the math and reading scores from the 9th graders at Thomas High School originally were helping the numbers in the district summary. Since we have now replaced those scores with NaN, the new scores in the district summary have suffered slightly.

---
### How is the School Summary Affected?
After replacing the 9th grade math and reading scores for Thomas High School in our challenge notebook, we were able to observe a few affects on the per school summary:

1. The % Passing Math fell sharply for Thomas High School. Before taking out the scores, the % passing math was about 93.27%. However, after taking out the scores, this metric dropped drastically all the way down to 66.91%

2. The % Passing Reading for Thomas High School also fell sharply. This metric dropped from 97.30% all the way down to 69.66% after replacing the scores.

3. The % Overall Passing for Thomas High School declined as well. Before replacing the scores, the Overall % Passing was 90.94-90.95% depending on rounding. However, after removing the scores, this metric fell to 65.07% on the new per school summary.

Overall, one can conclude that replacing the 9th grade math and reading scores for Thomas Highschool had a drastic negative impact on the schools numbers according to the school summary dataframe.

---
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
After recalculating the top and bottom most performing schools, we were able to observe that replacing the nonth graders' math and reading scores had a large negative affect on Thomas High School's performance relative to the other schools.

Originally, Thomas High School's performance in terms of % Overall Passing was within the top 5 performing schools, sitting at #2 behind only Cabrera High School. However, after replacing the ninth grade math and reading scores, Thomas High School's performance was changed to be worse than before when comopared to other schools. The new ranking for Thomas High School was 8th out of a possible 15 total schools

---
### How does replacing the ninth-grade scores affect the following?
#### Math and Reading Scores by Grade
By replacing the ninth grade scores, there were a few observed effects on the Math and reading scores per grade. 

First the average of ninth grade math scores when taking all schools decreased just slightly. The average for ninth graders went from 80.35 to 80.12. The math scores for the other grades were not affected.

Second, the average of the ninth grade reading scores when taking all schools decreased slightly as well. This moved from 82.52 down to 82.42 (or 82.43 with rounding). The reading scores for the other grades were also not affected.

---
#### Scores by School Spending
After replacing the values for ninth grade math and reading scores, there were some effects observed for the scores by school spending.

1. The math scores by school spending barely changed. The $630-$644 bin saw the only change: a tiny drop from 78.52 to 78.50
2. The Reading scores by school spending had a slight increase in the $630 - $644 bin. The score went up from 81.62 to 81.64

*One could argue that this is too small to even constitute a change. It is reasonable as well to say that the average scores by School Spending experienced NO CHANGE*

3. For schools that spend $630 - $640 per student, The % Passing Math experienced a negative change: dropped from 73% to 67%
4. For schools that spend $630 - $640 per student, The % Passing Reading also experienced a negative change: The score dropped from 84% to 77%
5. For schools that spend $630 - $640 per student, The % Overall Passing experienced a negative change: The score dropped from 63% to 56%

---
#### Scores by School Size
After replacing the values for ninth grade math and reading scores, there were some effects observed for the scores by school size.

1. The Average Math Score for Medium schools did not change. The score remained at 84%
2. The Average Reading Score for Medium schools also did not change. The score remained at 83.9%

3. The % Passing Math for Medium schools received a negative change. The score dropped from 94% to 88%
4. The % Passing Reading for Medium schools received a negative change. The score dropped from 97% to 91%.
5. The % Overall Passing for Medium schools received a negative change. The score dropped from 91% to 85%.

---
#### Scores by School Type
Lastly, After replacing the values for ninth grade math and reading scores, there were some effects observed for the scores by school type.

1. The Average Math score AND the Average Reading Scores did not change for the Charter schools. These scores both remained at a rounded 83.5% and 83.9% respectively

2. The % Passing Math dropped for Charter schools. It fell from 94% to 90%
3. The % Passing Reading also dropped for Charter schools. It fell from 97% to 93%
4. The % Overall Passing also dropped for Charter schools. It fell from 90% to 87%
