# School_District_Analysis

## Overview of Project
Maria is our client who works for the school district and has requested us to analyze student funding and student standardized test scores to provide insights about performance trends and patterns. These insights will be used to inform discussions and make stratigic decisions at the school and district level. 

The main deliverables for the anlysis are:
- High level snapshot of each districts key metrics
- Overivew of key metrics for each school
- Top 5 and bottom 5 performing schools, based on overall passing rate (math and reading scores)
- Average math score by students in each grade level at each scool
- Average reading score by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size
- School performance based on the type of school  

The school board has noticed that there may be evidence of academic dishonesty for nine graders in Thomas High School (THS). Maria has requested that we run the analysis again and replace the nine graders at THS with NaNs and report back on how these changes affected the overall analysis. 
## Results
1. How is the district summary affected?
District summary had no considerable variances:
- Average Math Score had a drop of 0.1%  vs original
- Average Reading Score remained the same at 81.9%
- % Passing Math with a drop of 0.2% vs original
- % Passing Reading decreased by 0.1% vs original
- % Overall Passing dropped by 0.3% vs original

 ![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####

2. How is the school summary affected?
The school summary is only affected in Thomas High School, since no other scores were altered. 
Just for practice I merged both school summaries and compared each score column, giving me the desired result of only seeing variance in Thomas High School.
![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Based on % Overall Passing Thoms Highs School dropped from second place to 8th place
![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####

4. How does replacing the ninth-grade scores affect the following
    - Math and reading scores by grade
        - It does not affect the other school grades since they were not altered. The only school that is impacted only for 9th grade is THS
    - Scores by school spending
        - The spending summary was not affected by the replacement of 9th grade scores
        ![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####
    - Scores by school size
        - Scores by school size was not affected by the replacement of 9th grade scores
        ![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####
    - Scores by school type
        - Scores by school size was not affected by the replacement of 9th grade scores
        ![Alt text](https://github.com/Jimena-QM/Election_Analysis/blob/main/Resources/Election_results_terminal.PNG "Terminal Election Results") ### MODIFY ####




## Summary
The values that were affected by the change in school district are:

District summary had small variances in:
- Average Math Score had a drop of 0.1%  vs original
- Average Reading Score remained the same at 81.9%
- % Passing Math with a drop of 0.2% vs original
- % Passing Reading decreased by 0.1% vs original
- % Overall Passing dropped by 0.3% vs original

Thomas High School dropped from secondn place to eight place when ranked based on % Overall Passing
