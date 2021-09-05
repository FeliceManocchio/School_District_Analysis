# School_District_Analysis
School standardized test analysis
## Overview and Purpose
### Analysis Objective
The data in this module contains standardized testing results for math and reading within local schools. The school board suspects our original analysis of student performance is skewed due to academic dishonesty from the 9th graders in Thomas High School. We must first remove the scores of the 9th graders in Thomas High School then re-analyze the performance of all the students on the standardized test with respect to the math and reading scores. After we come up with the new analysis we can then back track and look at how much the scores were affected by removing the 9th graders from Thomas High School.
## Results
### Original vs. New District Analysis
Below is an image of the original analysis we ran within the district with the 9th graders test scores factored in, followed by the new district analysis. We can see that on a district level there was not a change in overall performance within math and reading test scores.  
![Original_district_analysis](/Images/Original_district_analysis.png)
![New_district_analysis](/Images/New_district_analysis.png)

### Original vs. New School Summary Metrics
The below images showthe original analysis of Thomas High School's standings with the 9th graders included and the second image shows the filtered analysis with the 9th graders removed. From these images we can see the following changes to each of the permance metrics on the test.
- In regards to Avg math score with the 9th graders Thomas High School scored 83.41%, without 9th graders they scored 83.35%
- In regards to Avg reading score with the 9th graders Thomas High School scored 83.84%, without 9th graders they scored 83.89%
- In regards to % Passing Math with the 9th graders Thomas High School scored 93.27%, without 9th graders they scored 93.18%
- In regards to % Passing reading with the 9th graders Thomas High School scored 97.30%, without 9th graders they scored 93.01%
- In regards to % Passing overall with the 9th graders Thomas High School scored 90.94%, without 9th graders they scored 90.63%
![school_summary_og](/Images/school_summary_og.png)
![school_summary_new](/Images/school_summary_new.png)

### Affect of 9th Grader Replacement in Overall Standings
In overall scoring of thest with math and reading combined the removal of the 9th graders reduced the overall performance percent by less than a half of a percent which has Thomas High School still command a strong position in the top 5 performers as shown in the images above. 

Below we will look deeper as to how much the metrics were affected by removing the 9th graders from Thomas High School.
- Math and Reading scores by grade were essentially unaffected except for the fact the 9th grade scores returned as NaN for Thomas High School. 10th, 11th, and 12th grader scores all remained the same for both analysis.
- In regards to score by school spending find that they remain within the same bin in accordance to 
![spending_og](/Images/spending_og.png)
![spending_new](/Images/spending_new.png)
- In regards to scores by school size still remained unaffected as Thomas High School still stood within the Medium 1000-2000 school bin
- In regards to scores by school type the standings also go unchanged
## Summary
