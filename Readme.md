# Employee-Attrition-Prediction

## Objective
To predict employee attrition in Python using machine learning

## Data Description 
The dataset contains information on 25491 employees across 10 different attributes. Each row represents an employee, and each column provides specific details about the employee's characteristics:

1.satisfaction_level: A measure of how satisfied the employee is with their job, ranging from 0 to 1

2.last_evaluation: Time since the employee's last performance evaluation, measured in years.

3.number_projects: The total number of projects the employee has completed while working at the company.

4.average_monthly_hours: Average number of hours the employee spends at the workplace each month.

5.time_spend_company: Number of years the employee has been with the company.

6.Work_accident: Indicates whether the employee has had a workplace accident (1 if yes, 0 if no).

7.left: Binary variable indicating whether the employee left the company (1) or not (0).

8.promotion_last_5years: Indicates whether the employee was promoted in the last five years (1 if yes, 0 if no).

9.sales: The department in which the employee works.

10.salary: Relative level of salary categorized as low, medium, or high.

## Approach
We conducted a project to analyze employee turnover using Python's Scikit-Learn library. We employed three different types of machine learning models—Logistic Regression, Random Forest, and Support Vector Machine—to predict whether employees would leave the company. After building these models, we evaluated their performance by measuring their accuracy. This allowed us to assess how well each model could predict employee attrition based on the dataset provided.
