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
Initial Analysis

<img width="858" alt="Screen Shot 2022-07-12 at 12 52 50 AM" src="https://user-images.githubusercontent.com/107584361/178548895-d8200096-72b9-49fa-b342-fa9d1312fd55.png">

Updated analysis

<img width="835" alt="Screen Shot 2022-07-12 at 12 54 01 AM" src="https://user-images.githubusercontent.com/107584361/178548919-d99f8da5-20da-4866-92b5-3b0b3d2e8112.png">

* There was a slight change by school spending groups scores for the $630-644 per student grouping as this is where Thomas High School is grouped. 
* However the change is small with each metric changing less than 0.1 percentage points (or change of less than 0.1%).

#### Scores by school size
Initial Analysis

<img width="782" alt="Screen Shot 2022-07-12 at 12 55 02 AM" src="https://user-images.githubusercontent.com/107584361/178550183-e8bc4231-f7fb-4faa-bc5d-aa2de5df02f8.png">

Updated Analysis

<img width="776" alt="Screen Shot 2022-07-12 at 12 55 54 AM" src="https://user-images.githubusercontent.com/107584361/178550247-2c274610-190b-4070-93dc-3be9b3db1795.png">

* There is no change or impact after the updated Thomas High School 9th grade to NaN. 
* As the percentage is rounded to zero decimal. There is no much change in the overall performance of schools by school size.

#### Scores by school type
Initial Analysis

<img width="727" alt="Screen Shot 2022-07-12 at 10 10 31 AM" src="https://user-images.githubusercontent.com/107584361/178552221-aa37e6ba-7ed6-4eb6-b284-ea929ef15c1e.png">

Updated Analysis

<img width="726" alt="Screen Shot 2022-07-12 at 10 11 01 AM" src="https://user-images.githubusercontent.com/107584361/178552306-ac859243-b8db-4b42-b476-4b793722bdad.png">

* Thomas High School is a charter school type. The hundredths place was needed to see the nominal changes.
* There is no noticeable change by school type.
# Summary
Major changes to the school district analysis after reading and math scores have been replaced are:
* The first replacement of the 9th grade values with Nan bring down all the scores of Thomas High School. But then, at the end of our Analysis, we replace the school summary code with code that only counts the 10th-12th grade passing data. This brings our data back up. In our final dataframe therefore:
  * The grades % increased for Thomas High School so it went from a low performing to a high performing school
  * The % Passing Math Scores for Thomas High School returned back up to 93 from 66.9
  * The % Passing Reading returned back up to 97 from 69.6
  * The overall percentage of the passing returned back up to 90 from 65.

<img width="1017" alt="Screen Shot 2022-07-12 at 10 25 10 AM" src="https://user-images.githubusercontent.com/107584361/178558352-e3344d36-3966-435d-8526-b7779fba4430.png">

<img width="1001" alt="Screen Shot 2022-07-12 at 10 25 50 AM" src="https://user-images.githubusercontent.com/107584361/178558386-1b8f14ea-933d-466a-96a0-52c025f338f0.png">




