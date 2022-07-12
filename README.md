# School_District_Analysis

Click here to view data:

[schools_complete.csv](https://github.com/morganfredrick/School_District_Analysis/blob/main/Resources/schools_complete.csv) // 
[students_complete.csv](https://github.com/morganfredrick/School_District_Analysis/blob/main/Resources/students_complete.csv)

Click here to view file:

[PyCitySchools_Challenge](https://github.com/morganfredrick/School_District_Analysis/blob/main/PyCitySchools_Challenge.ipynb)

## Overview

The purpose of this analysis is to replace the inaccurate data for the 9th graders at Thomas High School while keeping the rest of the data intact. The analysis provided insight into the performance of schools within the district, namely math and reading scores, and their relationship to other metrics. To showcase trends in school performance, the analysis focuses on the following:

1.	The district summary, which includes the total number of students, the total number of schools, total budget, math and reading averages, and math, reading, and overall passing percentages.
2.	The school summary, which includes, school type, number of students, school budget, average math and reading scores and math, reading, and overall passing percentages for each school.
3.	The top 5 and bottom 5 performing schools, based on the overall passing rate.
4.	The average math and reading scores for each grade level (9th, 10th, 11th and 12th) from each school.
5.	The math and reading scores grouped by the following:
     - Spending ranges per students
     - School size
     - School type

The analysis will assist the school board and superintendent in making decisions regarding the school budgets and priorities.

## Data Results

Based on the concerns for academic dishonesty in both math and reading scores among Thomas High School ninth graders, the schoolboard wants to uphold state-testing standards for this school only. The grades for math and reading in Thomas High School 9th graders will be replaced with NaNs, while keeping the rest of the data intact as you can see below with the average math and reading scores, respectively.

![avg_math_scores](https://user-images.githubusercontent.com/104293158/178397641-40996fac-343c-4a7c-bfda-d44e4a8da74a.PNG)
![avg_reading_scores](https://user-images.githubusercontent.com/104293158/178397656-55e27b35-82cb-4634-8755-efd62382bfb2.PNG)


In the following analysis, you can see the grades and averages prior to replacing the scores with Nan compared to other schools:

![school_original_metrics](https://user-images.githubusercontent.com/104293158/178400329-30103c95-47a1-43c0-8fef-06f9701f2d9e.PNG)

After removing certain metrics, the results remain fairly similar with the exception of the averages and percent passing within Thomas High School:

![school_Nan_metrics](https://user-images.githubusercontent.com/104293158/178400341-fe20e9ae-2472-4610-9938-0c007ce5dd28.PNG)


## Summary
The four major changes that occurred are:

  - Number of total students
  - Number of students counted at Thomas High School
  - Average math and reading scores
  - Overall percentages for math and reading at Thomas High School

It is clear the removal of data implies a decrease in the count of total students overall, but specifically Thomas High School for this analysis. Since the population amount decreased, leading to a minimal change in average scores and score percentages, it can be assumed that the removal of the math and reading scores of 9th graders at Thomas High School did not play as significant a weight as it was imagined to.

