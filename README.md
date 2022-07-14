
## Module 4, Deliverable 3:

# School_District_Analysis


## 1.	Overview of the school district analysis: 

In this challenge we are helping Maria, who is a chief data scientist for city school districts. We need to aggregate the data which are obtained from the standardized tests and analyze them for reporting and presenting the insights about the performance trends and patterns. This information will be helpful to school board in making informed decision about the school budgets and other priorities.

Later, the school board detected some problem with the reading and math grades for Thomas High School and suspected an academic dishonesty. So, it was notified to us and was asked to replace the math and reading scores with NaNs for the Ninth-Grade students while keeping the rest of the data unchanged. The whole exercise for school district analysis need to be repeated and to produce a report describing the changes in the overall analysis.

## 2.	Results: 

**•** In the first step, reading and Math score for the Ninth-Grade students was replaced with NaN and then merged the “student data” and “school data” into a single dataset.

**•** The number of students passing in Math is changed from 29370 to 28939 and passing reading is changed from 33610 to 33158. Similarly, the percentage passings for math and reading also changed from 74.9808 to 74.7603 and from 85.805 to 85.659 respectively.

**•** Hence, the over all passing count and percentage also decreased from 25528 to 25105 and 65.172 to 64.855

### Figure 1: Showing the district summary.


![Figure 1](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/district_summary.png)


### Figure 2: Showing the per school summary.


![Figure 2](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/per_school_summary.png)


### Figure 3: Showing the top five and bottom five schools based on the over all passing percentage.


![Figure 3](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/Top_five_Bottom_five_Schools.png)


### Figure 4: Grade wise math score for each school.


"nan" value is presented of the Thomas High School 9th grade.


![Figure 4](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/math_score_by_grade.png)


### Figure 5: Grade wise reading score for each school.


"nan" value is presented of the Thomas High School 9th grade.


![Figure 5](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/reading_score_by_grade.png)


## Scores by school spending


### Figure 6: Showing the summary based on spending/expenditure and the scores for Math, reading and overall passing.


![Figure 6](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/summary_by_spending.png)


## Scores by school size


### Figure 7: Showing the summary based on the size of the school and the scores for Math, reading and overall passing.


![Figure 7](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/summary_by_size.png)


## Scores by school type: 


### Figure 8: Showing the summary based on the type of the school and the scores for Math, reading and overall passing.


![Figure 8](https://github.com/gothwalritu/School_District_Analysis/blob/main/screenshots/summary_by_type.png)



## 3.	Summary

Following are the Summarizing points for changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School was replaced with NaNs:

**a.**	After replacing the reading and math score for the 9th grade of Thomas High School, the values for the number of students passing in math and reading in Thomas High School is different now, which is also affecting the total number of students passing in Math and reading in 9th grade as well as for total students passings.

**b.**	Earlier to replacing the Thomas High School score, there was no NaNs value in the data, but now the data is having the NaNs value which would make the data a bit less reliable for future use. Also, adding the NaN will affect the accuracy of the predictions as there are students, who are accounted in the total count of the students but not having any score.

**c.**	The average score for students passing in math and reading is different and have a reduced value. However, it is not seen in the value as the difference is very small which is rounded off in calculations.

**d.**	The overall passing percentage for Thomas High School is also changed.

