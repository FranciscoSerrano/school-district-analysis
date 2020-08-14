# PyCity Schools

## Overview
### Purpose
The purpose of this analysis is to assist Maria with finding trends in the data for the counties high school stusents reading and math scores to determine funding for each school.

### Background
Maria has asked us to assist her with finding trends in the data in order to determine funding for the high schools in the county based on the students reading and math scores. The school board determined that the results for the 9th graders at Thomas High School may be dishonest. Therefore, we have remmoved all test scores for those students.

## Results
- How is the district summary affected?
  - When Thomas High School 9th graders scores were removed the following occured:
    - The average math score decreased by .1 points from 79.0 to 78.9
    - The average reading score remained the same at 81.9
    - The percentage of students passing math decreased by 1% from 75% to 74%
    - The percentage of students passing reading decreased by 1% from 86% to 85%
    - The overall percentage of passing students decreased by 1% from 65% to 64%

- How is the school summary affected
    - The diffrence in the school summary after the change shows that the average passing scores for 
      reading and math as well as the overall passing grades see a significant drop. 
    
- How does replacing the ninth graders' math and reading scores affect Thomad High School's performance relative to the other schools?
  - Thomas High School now ranks 10th in the county in math, where it had previously ranked 12th. The 
    ranking for reading does not change from 9th place when the schores are removed.

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - Other than 9th grade no other grades where affected by this change. The only affected school was  
      Thomas High School.
  - Scores by school spending
    - Thomas High School is in the $630 - $644 per student spending bucket. When Thomas High School 9th grade reading and math scores are removed, all passing rates for that bucket decrease significantly. However, the averages stayed the same.
      - The percent of students passing math decreased 6% from 73% to 67%
      - The percent of students passing reading decreased 7% from 84% to 77%
      - The overall passing percentage decreased 7% from 63% to 54%.
  - Scores by school size
    - Thomas High school has 1635 students total which puts them in the medium school size bucket. When Thomas High school removes the 9th grade scores for reading and math, the passing rate for math, reading, and the overall passing rate decrease by 6%. Again, the average scores for reading and math do no change.
  - Scores by school type
    - Thomas High School is a Charter School. Again, the average scores for both math and reading stay the same, however both the passing rate for reading and math decrease 4% and the overall passing rate decreases by 3%.

## Summary
1. The AVG reading and math scores saw little difference which means one can conlcude that the NaN values had little significance on this metric.
2. The percent of students passing math had decreased from 93% to 67% 
3. The percent of students passing reading had decreased from 97% to 70%
4. The amount of overall passing grades decreased from 91% to 65%