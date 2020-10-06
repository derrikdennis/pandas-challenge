# My Analysis of PyCity Schools - Pandas Challenge

If you would like to see my findings, please scroll down to the findings section.

## Background

For a better understanding of how Python Pandas works, we were given the option of choosing between two different categories.
I chose Academy of Py. In this assignment, I was given the role of Chief Data Scientist for PyCity Schools and charged with the task of analyzing the district-wide standardized test scores.
This analysis would be used to make strategic decisions regarding future school budgets and priorities.

## Reporting Steps

My final report included the following information in tabluar form:

### District Summary

- I created a high level snapshot of the district's key metrics including:
  - Total Schools
  - Total Students
  - Total Budget
  - Average Math Score
  - Average Reading Score
  - % Students - Passing Math
  - % Students - Passing Reading
  - Overall Passing Rate of Students

### School Summary

- I created a table that summarizes key metrics about each school, including:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Rading Score
  - % Students - Passing Math
  - % Students - Passing Reading
  - Overall Passing Rate

### Top Five Performing Schools (by Overall Passing Rate)

- I created a table that highlighted the top five performing schools based on Overall Passing rate. Specficially, I included:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Reading Score
  - % Students - Passing Math
  - % Students - Passing Reading
  - Overall Passing Rate

### Bottom Five Performing Schools (by Overall Passing Rate)

- I created a table that highlighted the bottom five performing schools based on Overall Passing rate. Specficially, I included:
  - School Name
  - School Type
  - Total Students
  - Total School Budget
  - Per Student Budget
  - Average Math Score
  - Average Reading Score
  - % Students - Passing Math
  - % Students - Passing Reading
  - Overall Passing Rate

### Math Scores by Grade

- I created a table that lists the average Math Score for the students of each grade level of the school.

### Reading Scores by Grade

- I created a table that lists the average Reading Score for the students of each grade level of the school.

### Scores by School Spending

- I created a table that looked at school performances based on average Spending Ranges. These spending ranges per student were:
  - < \$600
  - $600 - $624
  - $625 - $649
  - > \$650
- The table had the following information
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - Overall Passing Rate

### Scores by School Size

- I created a table that looked at school performances based on school size. The sizes I chose were:
  - Small schools: < 1800 students
  - Medium schools: 1800-3600 students
  - Large schools: > 3600 students
- The table had the following information
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - Overall Passing Rate

### Scores by School Type

- I created a table that looked at school performane by type of school - charter or public. The table hd the following information:
  - Average Math Score
  - Average Reading Score
  - % Passing Math
  - % Passing Reading
  - Overall Passing Rate

# Findings

Here are my two observatable trends:

1.  Charter school scored had higher overall passing rates overall and within both math and reading comprehensions. On average, charter school had a 95.17% passing rate overall. This is 22 points higher than district schools which had a 73.71% overall passing rate. As is pertains to math: charter schools passing rate was 93.70% while district schools had a passing rate of 66.52%. In reading comprehension, charter schools had a pass rate of 96.65% compared to district schools at a rate of 80.91%. Attention needs to be paid to what we can do to raise district schools scores higher.

2.  Throwing additional funding towards these schools might not be the best way to go. Those that spend the highest amount of money at over $650 per student only saw an overall passing rate of 73.69% whereas those that spent less than $600 per student had a passing rate of 95.12. The sweet spot seems to be spending between $600 and $624. The passing rate of this bucket was slightly higher than spending less than \$600 at 95.27%.

Please have a look at the DataFrames in the Jupyter Notebook for additional findings.
