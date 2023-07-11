<!-- # pandas-challenge

    This project involves analysis of district-wide standardized test results using Pandas DataFrames. The goal is to provide insights and identify trends in school performance to help the school board and mayor make strategic decisions regarding future schcool budgets and priorities.

Background 
    
    As the new Chief Data Scientist for the city's school district, the task is to analyze district-wide standardized test results and make informed decisions regarding future school budgets and priorities. The dataset includes math and reading scores for each student, as well as information about the schools they attend. The key metrics to be calculated and analyzed include district-level summaries, school-level summaries, highest-performing and lowest-performing schools, grade-level scores, school spending analysis, school size analysis, and school type analysis.

Inside this Repository: 
* README.md File: The following file is the README.md file. You will find a background of the project and instructions on how to complete. 
* PyCitySchools Folder: This folder contains the PyCitySchools_starter.ipnyb file where you will find the entire analysis
* Analysis Folder: This folder contains the Written_Analysis that provides multiple insights into school performance and trends.

Instructions

1. District Summary
    Calculate the total number of unique schools, total students, total budget, average math score, average reading score, percentage of students passing math, percentage of students passing reading, and overall passing percentage.
    Create a DataFrame named "district_summary" to summarize the above metrics.

2. School Summary
    Calculate key metrics for each school, including the school name, school type, total students, total school budget, budget per student, average math score, average reading score, percentage of students passing math, percentage of students passing reading, and overall passing percentage.
    Create a DataFrame named "per_school_summary" to summarize the above metrics.

3. Highest-Performing Schools (by % Overall Passing)
    Sort the schools by the overall passing percentage in descending order and display the top 5 performing schools.
    Save the results in a DataFrame named "top_schools".
    Lowest-Performing Schools (by % Overall Passing)

    Sort the schools by the overall passing percentage in ascending order and display the bottom 5 performing schools.
    Save the results in a DataFrame named "bottom_schools".

4. Math Scores by Grade
    Calculate the average math score for students in each grade (9th, 10th, 11th, and 12th) at each school.
    Create a DataFrame named "math_scores_by_grade" to summarize the average math scores.
    Reading Scores by Grade

    Calculate the average reading score for students in each grade (9th, 10th, 11th, and 12th) at each school.
    Create a DataFrame named "reading_scores_by_grade" to summarize the average reading scores.

5. Scores by School Spending
    Categorize schools based on average spending ranges per student.
    Calculate the average math score, average reading score, percentage of students passing math, percentage of students passing reading, and overall passing percentage for each spending range.
    Create a DataFrame named "spending_summary" to summarize the above metrics.
    Scores by School Size

    Categorize schools based on their size (small, medium, large).
    Calculate the average math score, average reading score, percentage of students passing math, percentage of students passing reading, and overall passing percentage for each school size.
    Create a DataFrame named "size_summary" to summarize the above metrics.

6. Scores by School Type
    Categorize schools based on their type (charter or district).
    Calculate the average math score, average reading score, percentage of students passing math, percentage of students passing reading, and overall passing percentage for each school type.
    Create a DataFrame named "type_summary" to summarize the above metrics.