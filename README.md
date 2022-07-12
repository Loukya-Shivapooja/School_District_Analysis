# School_District_Analysis
Analysis of School District using pandas
# Overview of the School District Analysis:
City school districts are responsible for analyzing data, at the student and school level, from multiple sources and in various formats, which ultimately provide insight on how well students are performing, the size of school budgets and overall priorities. For the School District Analysis project, student’s math and reading scores will be analyzed, along with information on the schools they attend. By aggregating this data, trends on school performance can be identified and utilized to implement strategic decisions at the school and district level.
## Purpose
The purpose of this project is to evaluate the math and reading grades for Thomas High School students. A key dataset utilized in evaluating the analysis, indicates that there is evidence of academic dishonesty, as the grades for ninth grade students appear to have been altered. In an effort to uphold state-testing standards, a comparative analysis will be completed which will indicate whether replacing math and reading scores for Thomas High School ninth grade students with NaNs, which means ‘not a number’ and cannot be equal, will affect the overall analysis.
## Resources 
CSV Files: schools-complete.csv, students_complete.csv, clean_student_complete.csv

Jupyter Notebook Files: PyCitySchools.ipynb, PyCitySchools_Challenge.ipynb
# Results
### District Summary 
Initial Analysis
<img width="1124" alt="Screen Shot 2022-07-11 at 3 42 47 PM" src="https://user-images.githubusercontent.com/107584361/178409736-df15d40e-8b12-4b3d-9a3f-fad0e38d230f.png">
updated Analysis
<img width="1139" alt="Screen Shot 2022-07-11 at 3 43 36 PM" src="https://user-images.githubusercontent.com/107584361/178409795-f964bc78-b6fb-4ae9-8fb2-50d635074afb.png">

* After updating the data, **The District Summary** data did not had large impact. Total Schools, Total Students and Total Budget data did not change.
* Average math score dropped just by 0.1 , i.e. from 79 to 78.9 and % passing math also showed 0.2% drop i.e. from 75% to 74.8% respectively.
* Aveerage reading score remained same i.e. 81.9, % Passing Reading showed 0.3% drop i.e. from 86% to 85.7% respectively.
* overall passing percentage decreased by 0.1% i.e. from 65% to 64.9%.
### School Summary
Initial Analysis
<img width="1106" alt="Screen Shot 2022-07-11 at 10 47 59 PM" src="https://user-images.githubusercontent.com/107584361/178418637-cd314492-8e0d-44a8-81e8-5596ea8ea73a.png">
Updated Analysis
<img width="1023" alt="Screen Shot 2022-07-11 at 11 48 35 PM" src="https://user-images.githubusercontent.com/107584361/178426735-0d344670-93da-49b8-805b-f70d84406373.png">
* The **School Summary** data remains unaffected for all schools except for Thomas High School.
* Average Math Score and Average Reading scores for Thomas High School has a very slight change.
* % Passing Math score and Reading for Thomas High School came considerable down from 93.27% to 66.91% and 97.31% to 69.66% respectively.
* % Overall passing students for Thomas High School came down from 90.95% to 65.08%.
### By Replacing the ninth graders’ math and reading scores of Thomas High School’s performance relative to the other schools.
Initial Analysis
<img width="1014" alt="Screen Shot 2022-07-12 at 12 06 45 AM" src="https://user-images.githubusercontent.com/107584361/178429924-6d16cafa-b5d1-4cd3-8763-0ab60f7366cb.png">
Updated Analysis
<img width="1005" alt="Screen Shot 2022-07-12 at 12 07 28 AM" src="https://user-images.githubusercontent.com/107584361/178430011-1a4fbe95-4c21-4c04-88d3-1d1d1ee08252.png">
* The ranking of the top schools including Thomas High School was not affected by the update.
* While the average math, reading and overall scores at Thomas High School were impacted with the update, the changes were not enough to change its relative ranking versus other schools. The changes only had a small impact of less than a change of 1 percentage point on each metric.
### Replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
Initial Analysis

<img width="325" alt="Screen Shot 2022-07-12 at 12 31 55 AM" src="https://user-images.githubusercontent.com/107584361/178437026-e662756c-f823-4519-bf41-35513e891996.png">        <img width="326" alt="Screen Shot 2022-07-12 at 12 32 39 AM" src="https://user-images.githubusercontent.com/107584361/178437074-99aef548-594b-434d-8740-72688d29063a.png">

Updated Analysis

<img width="330" alt="Screen Shot 2022-07-12 at 12 34 43 AM" src="https://user-images.githubusercontent.com/107584361/178437198-5f11ca5e-ccb9-46f7-9a94-5c57707d48de.png">         <img width="335" alt="Screen Shot 2022-07-12 at 12 35 27 AM" src="https://user-images.githubusercontent.com/107584361/178437251-6e55606f-0482-405e-a992-f4ecd689f9ca.png">

* The only score that is impacted on this DataFrame is that the grade 9 students at Thomas High School have Nan instead of a grade for both math and reading.
#### Scores by school spending










