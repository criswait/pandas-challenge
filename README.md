School District Analysis

**Overview**
This project analyzes data from a school district to assess the performance of schools based on various metrics, such as average test scores, passing rates, and budget allocation. The analysis is broken down by school type, size, and spending per student.

**Files in This Repository**
- schools_complete.csv: A dataset containing school-level data, including budget and student population.
- students_complete.csv: A dataset containing student-level data, including math and reading scores.
- analysis.py: The Python script used to process and analyze the data.
- README.md: This file, providing an overview of the project and instructions.

**Analysis Steps**
1. District Summary
- Calculate the total number of schools, students, and the overall budget.
- Compute the average math and reading scores.
- Calculate the percentage of students who passed math, reading, and both subjects.

2. School Summary
- Determine each school's type, total number of students, budget, and per capita spending.
- Calculate average math and reading scores for each school.
- Compute passing rates for math, reading, and overall for each school.
- Summarize the data into a comprehensive DataFrame.

3. School Performance Analysis
- Top and Bottom Performing Schools: Identify the top 5 and bottom 5 schools based on overall passing rates.
- Performance by Grade: Calculate average math and reading scores by grade (9th, 10th, 11th, 12th) for each school.
- Performance by Spending Per Student: Analyze the relationship between school spending and performance.
- Performance by School Size: Examine how school size affects performance.
- Performance by School Type: Compare the performance of charter schools versus district schools.

**Instructions to Run the Analysis**
1. Clone the repository to your local machine.
2. Ensure you have Python installed (preferably version 3.x).
3. Install the necessary dependencies using pip install -r requirements.txt (if you provide a requirements.txt).
4. Run the analysis script analysis.py to generate the results.

**Dependencies**
- Python 3.x
- pandas

**Disclaimer**
  This readme file was generated with the help of ChatGPT and customized by your truly,

  Cristian Waitman
