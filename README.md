# School_District_Analysis


## Overview of the school district analysis:
In this project, using the jupyter notebook to analysis the school district academy performance. Within the project usually work with jupyter notebook, Panda dataframe, Python, Pandas library and Numpy library.
We import the CSV files data from different schools and students to find the highest and lowest performance school base on calcuate the average from math score and reading score from different grade of school.

## Results: 

### How is the district summary affected?

![old_district_summary](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/old_district_summary.png)
![district_summary](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/district_summary.png)
In the project, repplace the 9th grade math and reading scores with NaN for Thomas High school. That's mean Thomas High school does have any 9th grade scores in math and reading. However, there not have big affected for district summary.
The old overall passing percentage drop down 0.1% from 65% to 64.9%. And the Thomas High school still not in the list of top 5 school.

### How is the school summary affected?

![10th_12th_school_summary](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/10th_12th_school_summary.png)
The ranking of the school is no affect by the udpate. The Thomas High School has high ovrerall passing percentage rate on 90.63% on 10th grade to 12th grade students.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

That is low affect Thomas High School's performance relative to the other schools because we can reveiw the math and reading by scroed. Because Thomas High School was in the bottom of 5 schools not matter math scores or reading scores. The only score will be impact on the DataFrame is the score of 9th grader at Thomas High School. Since, we used NaN instead of the score for 9th grade students.
There has slight different on scores by school spending, the percentage of the range on $630-644 get 0.1% decrease with each metric (or less than 0.1%). There will be same situation on school size and school type
Math and reading scores by grade
![math_scores_by_grade](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/math_scores.png)
![math_rading_scores_by_grade](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/math_reading_grade.png)
Scores by school spending
![old_scores_school_spending](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/old_scores_school_spending.png)
![scores_school_spending](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/scores_school_spending.png)
Scores by school size
![scores_school_size](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/scores_school_size.png)
Scores by school type
![scores_school_type](https://github.com/JoJofia/School_District_Analysis/blob/91d7a958d7c794b8011a88910d11a7be49ed83ba/Resources/scores_school_type.png)

## Summary: 
After replace the score for ninth grade at Thomas High school didn't have specific to show up the impact in data.However, the ninth grade student replace by NaNs casuse the overall passing percentage and average scores drop down by 0.1%. That's mean the math and reading score also decrease after without 9th grade data. Even though, the data didn't have the big affect on the result but the schoolboard still needs to understand its discrepencies.

