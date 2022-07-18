# School_District_Analysis
Summary below explains the results from my School_District_Analysis and how it compares with the results from the module.

*Overview of the school district analysis*

The purpose of this project is to help Maria analyze data on student funding and students' standardized test scores. data for analysis, reporting, and presentation for an entire School District to provide insights about performance, trends, and patterns. Our task is to aggregate the data and showcase trends in school performance. This analysis will help the school board and superintendent in making decisions regarding the school budgets and priorities. 
The School Board has asked Maria to re-analyze some data because there appears to be some anomalies in the data, in particular, math and reading scores of the 9th grade students from Thomas High School. Our analysis below will compare and contrast the Original version vs. Thomas High School version to find potential errors.

*Results:*

Was district summary affected?

District Analysis - Original
<img width="966" alt="District Summary OG" src="https://user-images.githubusercontent.com/106992995/179455792-98cdf0e7-7030-4a61-9c6e-0301669d3ade.png">


District Analysis - Thomas High School
<img width="951" alt="District Summary THS" src="https://user-images.githubusercontent.com/106992995/179455820-81536013-3c02-4eff-8f24-d6654e48a05e.png">

Outcome: There was not a large impact on adding NaNs to Thomas High School's 9th graders because there are only 461 students in 9th grade at Thomas High School, and given the total student count is 39,170, both math and reading scores were only off by a couple hundreths of a percent as a margin of error.


Was the school summary affected?

School Summary - Original

<img width="1006" alt="SchoolSummaryOG" src="https://user-images.githubusercontent.com/106992995/179456706-0710b36b-4a5e-49e1-a5c4-ef33b80627ca.png">


School Summary - Thomas High School

<img width="1058" alt="SchoolSummaryTHS " src="https://user-images.githubusercontent.com/106992995/179457446-a9460a98-bc0c-4c27-a908-24a5b71b65f4.png">


Outcome: The average math, reading and overall test scores at Thomas High School were impacted with the update, but they were not significant enough to change the school summary rank compared to the other schools measured. The ranking of the top schools, including Thomas High School, was not affected by the update.


How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The scores for Thomas High School were not impacted. See screenshots below for reference:

*Ninth graders’ math scores - Original*

<img width="229" alt="math_scores_by_gradeOG" src="https://user-images.githubusercontent.com/106992995/179459924-d892408f-c789-4396-b85c-389e503173dc.png">

*Ninth graders’ reading scores - Original*

<img width="231" alt="Reading_scores_by_gradeOG" src="https://user-images.githubusercontent.com/106992995/179459943-d05753fa-7727-4f32-9594-5fdebcf00516.png">

VS

*Ninth graders’ math scores - Thomas High School*

<img width="202" alt="Math_scoresTHS" src="https://user-images.githubusercontent.com/106992995/179460194-606b4b61-db8d-4555-99cc-aac62a965931.png">


*Ninth graders’ reading scores - Thomas High School*

<img width="190" alt="Reading_scoresTHS" src="https://user-images.githubusercontent.com/106992995/179460254-2bd3f86a-9703-4df1-8993-7c98f4028436.png">


**How does replacing the ninth-grade scores affect the following:**

Math and reading scores by grade?

*Math and Reading scores - Original*

<img width="332" alt="Math_scores_by_grade_OG" src="https://user-images.githubusercontent.com/106992995/179461505-bebcabc0-c95a-4a9e-9fcb-775f3e58b60a.png"> 
<img width="344" alt="Reading_scores_by_grade_OG" src="https://user-images.githubusercontent.com/106992995/179461523-340d8df6-475e-4c5a-9f61-7b2357b8fe3b.png">


*Math and Reading scores - Thomas High School*

<img width="319" alt="Math_scores_THS" src="https://user-images.githubusercontent.com/106992995/179461758-f823b088-59ec-4988-a5a3-6e112215a768.png">
<img width="320" alt="Reading_scores_THS" src="https://user-images.githubusercontent.com/106992995/179461776-3eeec8ff-2ff6-429d-bebb-7e24ed82485e.png">


**Scores by school spending**

*School Spending: Original*

<img width="887" alt="SpendingOG" src="https://user-images.githubusercontent.com/106992995/179462057-34c72092-518b-447a-ae89-a6888154f04c.png">


*School Spending: Thomas High School*

<img width="851" alt="SpendingTHS" src="https://user-images.githubusercontent.com/106992995/179462110-2dd85fff-b3fb-4bd2-83c8-14217ab7dbbc.png">





**Scores by school size**


Findings: No significant difference

*School Size: Original*

<img width="795" alt="Scores_by_School_sizeOG" src="https://user-images.githubusercontent.com/106992995/179462563-01dfbf21-9afa-4e8e-8c87-934085bac918.png">


*School Size: Thomas High School*

<img width="769" alt="Scores_by_School_sizeTHS" src="https://user-images.githubusercontent.com/106992995/179462581-591de92c-6eca-472e-be65-716529eb6288.png">




**Scores by school type**

*School Type Score: Original*

<img width="741" alt="School_typeOG" src="https://user-images.githubusercontent.com/106992995/179462916-977d6210-e643-47d3-9128-bc129b835e21.png">


*School Type Score: Thomas High School*

<img width="729" alt="School_typeTHS" src="https://user-images.githubusercontent.com/106992995/179462940-754423cf-5eea-46b0-ac1f-7b4efaf15b24.png">




**Summary:** 

**Four takeaways** in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.


*District Analysis* = changes to all scores were less than a half of a percent (0.5%) in total points, so no impact to school or student count.

*Top School Ranking* = no change to ranking even though some Thomas High School scores did change, they weren't significant enough to bump higher up on their ranking. 

*Scores by School Size* = no sigificant changes captured at all. 

*Scores by School Type* = small chages in both Charter type grouping and District type grouping for all scores was only captured with a change by less than 0.1%).
