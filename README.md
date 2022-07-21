## PyCity Schools

Created a Jupyter Notebook script to analyze district-wide standardized test results for students' reading and math as well as additional infromation on the schools they attend. Several snapshots of the aggregated data will show metrics based on multiple categories which are defined as district summary, school summary, highest and lowest performing schools, math and reading scores by grade, school spending, school size and school type. The passing score for math and reading was set to 70. 

### District Summary
* Created a DataFrame to show a high-level snapshot of the district-wide summary key metrics which include:
  * Total schools
  * Total students
  * Total budget
  * Average math and reading scores
  * Percent of students who passed math or reading
  * Percent of students who passed math and reading (overall passing percent)
  
### School Summary
* Created a DataFrame to summarize key metrics for each school which include:
  * School name
  * School type
  * Total students
  * Total school budget
  * Per-student budget
  * Average math and reading scores
  * Percent of students who passed math or reading
  * Percent of students who passed math and reading (overall passing percent)

### Highest- and Lowest-Performing Schools
* Created a DataFrame to summarize key metrics for the top- and bottom-5 performing schools based on overall passing percent using the same key metrics in School Summary.

### Math and Reading Scores by Grade
* Created a DataFrame to average math and reading scores for students of each grade level -- 9th through 12th -- at each school.

### Scores by School Spending, School Size and School Type
* Created tables to breadk down school performance based on average spending ranges per student, size and type. 
  * Average math and reading scores
  * Percent of students who passed math or reading
  * Percent of students who passed math and reading (overall passing percent)

<b>Files included:<b>
* PyCitySchools.ipynb
* schools_complete.csv (in resources folder)
* students_complete.csv (in resources folder)
