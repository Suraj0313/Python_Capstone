# Python_Capstone
# Overview
This project is a comprehensive data analysis task involving employee data and project management. The dataset consists of three main tables: Employee Data, Seniority Level Data, and Project Data. Using Python and data manipulation libraries, various tasks were performed to clean, merge, analyze, and enhance the dataset, simulating real-world data challenges. The tasks range from handling missing values to applying business logic for project performance evaluation.
# Key Features
- **Data cleaning and preprocessing:**
  - Imputed missing project costs using a running average with a for loop.
  - Split the full name column into separate first and last name columns for improved data organization.
- **Data Merging and Aggregation:**
  - Combined Employee, Seniority, and Project data into a single dataframe for a holistic analysis.
- **Project Bonus Calculation:**
  - Added a bonus column where employees who successfully completed projects received a 5% bonus based on project cost.
- **Designation Management:**
  - Decreased the designation level of employees whose projects failed and removed records where designation exceeded level 4.
- **Data Transformation:**
  - Applied appropriate titles (“Mr.” and “Mrs.”) based on gender and dropped the gender column to anonymize the data.
- **Employee Promotion:**
  - Promoted employees over 29 years of age by increasing their designation level using conditional logic.
- **Project Cost Summary:**
  - Created a new dataframe to summarize total project costs for each employee.
- **Querying Data:**
  - Filtered and displayed employee details based on specific criteria, such as the presence of the letter “o” in city names.

# Technologies Uses
- **Programming Language:**
  - Python
- **Libraries:**
  - Pandas for data manipulation and analysis
  - NumPy for numerical operations
  - Jupyter Notebook for code development and visualization

# Conclusion
This project demonstrates the practical application of data manipulation, business logic, and analytical problem-solving skills using Python. The tasks completed provide insights into handling real-world datasets, working with missing values, and applying logical rules to manage employee performance data. This project reflects the capability to handle data-driven tasks and make strategic decisions based on the output, ensuring readiness for real-world challenges.
