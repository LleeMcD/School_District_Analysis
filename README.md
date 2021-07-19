# School District Analysis
# Overview 
## Purpose
The school board for Thomas High School (THS) notified the district that its grade file for standardized test scores showed evidence of academic dishonesty. More specifically, the ninth grade reading and math scores appeared to have been altered. Although the school board did not know the full extent of the academic dishonesty, they expressed that they wanted to uphold state-testing standards. Based on this, the district asked that these grades be replaced with a "not a number" (NaN) designation for the math and reading scores while keeping the rest of the data intact. The school district analysis was repeated after the impacted scores were removed. The results are provided in the following sections of this report.
# Results
## Analysis 
- The summary results for the 15 schools in the district were as follows:
-	Total Students 39,170
-	Average Math Score 78.9%
-	Average Reading Score 81.9%
-	Average Passing Overall 64.9%
-	
![District_Summary_Results](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_THS_replaced_values_output.PNG)
- Charter schools held the top 5 positions with Thomas Highschool as the top second school with an overall passing score of 90.6%.
![Top_5](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_Top_5.PNG)
- The bottom five schools based on the overall passing scores were all district schools. 
![Bottom_5](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_Bottom_5.PNG)
- There was a negative correlation noted with student spending (increased spending, lower scores).
![Spending_Ranges_per_Student](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/Resources/PyCitySchools_Challenge_Student_Spending_Ranges.png)
- Smaller schools fared better the the larger ones.
![School_Size](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_Schools_by_Size.png)
- Charter schools had better scores than district schools.
![Budget_per_School_Type](https://github.com/LleeMcD/School_District_Analysis/blob/main/Resources/PyCitySchools_Challenge_Schools_by_Type.png)
## Summary
The removal of Thomas High School's ninth grade standardized test scores for math and reading had little impact on the overall findings. The math and reading scores were respectively, 79.0% and 81.9% before they were replaced. The subsequent math and reading scores were respectively, 78.9% and 81.9%, which reflects a negative change of 0.1% for the math scores. Thomas High School remains in the top five schools based on the overall percentage passing, math and reading scores. Additional observations are listed below:
- Student performance has an inverse correlation with school size.
- The amount of money spent per student did not have a positive correlation with performance, but an expense allocation was not provided so it may not be relevant.
- Students in smaller charter schools performed much better than students in the larger district schools. It is recommended that more data be collected to determine why these differences exit:
  - Demographics
  - Family circumstances
  - Houshold Income
  - Barriers (language, resources etc.)


