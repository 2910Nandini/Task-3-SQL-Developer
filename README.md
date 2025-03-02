# Task-3-SQL-Developer
Subqueries and Aggregations
# Objective
Use subqueries to extract insights from a dataset and perform data aggregations to summarize and analyze the data.
# Project Steps
Step 1: Database Setup
1. Table: Students
○ Fields:
■ student_id: Primary Key.
■ name: Name of the student.
■ math_score: Math test score.
■ science_score: Science test score.
■ english_score: English test score.
■ total_score: The sum of all scores for each student (optional if calculated dynamically).
2. Insert sample data with scores for Math, Science, and English for multiple students.
Step 2: Tasks to Perform
Task 1: Identify Top Students by Total Scores
● Use a subquery to calculate the total score (math_score + science_score + english_score) for each student.
● Use an ORDER BY clause to rank students by their total scores in descending order.
● Limit the results to show only the top students (e.g., top 5).
Task 2: Calculate Averages Based on Specific Conditions
● Use subqueries to filter and group data for average calculations:
○ Example 1: Calculate the average score of students who scored above 70 in Math.
○ Example 2: Calculate the average total score of students grouped by a specific condition, such as a score range (e.g., students scoring 200–250 in total).
Task 3: Find Second-Highest Math Scores
● Use a subquery to determine the highest Math score and exclude it in a second query to find the next highest value.
