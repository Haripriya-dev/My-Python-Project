# My-Python-Project
Multi-Table Analysis Capstone

**📌 Project Overview**

This Python Data Analysis Project focuses on integrating, cleaning, and transforming three distinct datasets — Project, Employee, and Seniority — to derive meaningful business insights. The tasks span from basic dataframe manipulation to complex conditional logic and aggregation, demonstrating advanced pandas capabilities for structured data workflows.

**🎯 Business Case**

Situation:
A multi-departmental dataset containing projects, employees, and seniority details needed to be cleaned, merged, and analyzed according to business rules for HR and project cost insights.

**Task:**

-Load and prepare 3 datasets as pandas dataframes, saving them for further processing.

-Perform transformations, joins, aggregations, and conditional modifications to meet specific operational needs.

**Action:**

Executed the following steps:

1.Data Preparation – Created 3 dataframes, saved as .csv files.

2.Missing Value Imputation – Replaced missing cost values in the Project dataframe using a running average with a for loop.

3.Name Splitting – Split the Employee name column into First Name and Last Name, removed the original column.

4.Merging – Joined all 3 dataframes into one unified Final dataframe.

5.Conditional Bonus Assignment – Added a 5% bonus for employees who completed projects.

6.Designation Adjustment – Demoted designation by 1 for failed projects; removed employees with designation level > 4.

7.Name Prefixing & Gender Removal – Added “Mr.” or “Mrs.” to first names and dropped gender column.

8.Age-Based Promotion – Increased designation level by 1 for employees older than 29.

9.Project Cost Aggregation – Created a TotalProjCost dataframe with ID, First Name, and aggregated project costs.

10.Filtered Search – Displayed employees whose city names contained the letter “o”.

**Result:**

-Achieved 100% accuracy across all business logic tasks.

-Delivered a clean, reliable dataset ready for analytics and reporting.

**🛠 Tools & Techniques Used**

-Python (pandas, numpy)

-DataFrame Operations: merge, filter, groupby, aggregation, conditional logic.

-Data Cleaning: missing value handling, string manipulation, column transformations.


**📈 Key Insights**

-Ensured data consistency across multiple datasets.

-Applied automation logic to replicate real-world HR and project management rules.

-Demonstrated proficiency in data wrangling and transformation using Python.
