# Excel Project: Data Jobs Dashboard 

![Dashboard.png](/Visualizations/Dashboard.gif)

## Introduction

This data jobs salary dashboard was created to help data science job seekers investigate salaries for their desired jobs based on their preferred location and job type.

The project is inspired by the online course [Excel for Data Analytics - Full Course for Beginners](https://www.lukebarousse.com/excel) by [Luke Barousse](https://github.com/lukebarousse).



### Dashboard File
My final dashboard is in [Data Science Jobs Dashboard](Data_Science_Jobs_Dashboard.xlsx).

### Excel Skills Used

The following Excel skills were utilized for analysis:

- **Charts**
- **Formulas and Functions**
- **Data Validation**

### Data Jobs Dataset

The [dataset](https://github.com/lukebarousse/Excel_Data_Analytics_Course/tree/main/0_Resources/Datasets) used for this project contains real-world data science job information from 2023, which provides a foundation for analyzing data using Excel. It includes detailed information on:

- **Job titles**
- **Salaries**
- **Locations**
- **Skills**

## Dashboard Build

###  Charts

####  Data Science Job Salaries in Canada - Bar Chart

<img src="/Visualizations/Data_Science_Salaries_Canada.jpg" alt="Salaries" width="70%" height="90%">


- **Excel Features:** Utilized bar chart feature (with formatted salary values) and optimized layout for clarity.
- **Design Choice:** Horizontal bar chart for  visual comparison of median salaries, making it easier to read.
- **Data Organization:** Sorted job titles by descending salary for improved clarity.
-  **Insights Gained:** This enables quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles with ML Engineers earning the highest- over $150,000 annualy.

####  Country Median Salaries - Map Chart

<img src="/Visualizations/Salary_Map.gif" alt="Salary_Map" width="70%" height="90%">


- **Excel Features:** Utilized Excel's map chart feature to plot median salaries globally.
- **Design Choice:** Color-coded map to visually differentiate salary levels across regions.
- **Data Representation:** Plotted median salary for each country with available data.
- **Visual Enhancement:** Improved readability and immediate understanding of geographic salary trends.
-  **Insights Gained:** Enables quick grasp of global salary disparities and highlights high/low salary regions.

###  Formulas and Functions

####  Median Salary by Job Titles


<img src="/Visualizations/excel_code.jpg" alt="Median Salary Code" width="50%">



- **Multi-Criteria Filtering:** Checks job title, excludes blank salaries, checks country, and schedule type.
- **Array Formula:** Utilizes `MEDIAN()` function with nested `IF()` statement to analyze an array.
- **Tailored Insights:** Provides specific salary information for job titles, regions, and schedule types.
- **Formula Purpose:** This formula populates the table below, returning the median salary based on job title, country, and type specified.

####  **Median Salary** Table for **Canadian Full-time** Data Science Roles

<img src="/Visualizations/median_salary_excel.jpg" alt="median_salary_excel" width="40%" height = "40%">


#### Dashboard Implementation

<img src="/Visualizations/dashboard_salary_output.jpg" alt="Dashboard_salary_output" width="40%" height = "40%">


####  Count of Job Schedule Type

<img src="/Visualizations/type_count_code.png" alt="type_count_code" width="50%">


- **Multi-Criteria Filtering:** This Excel formula ,similar to the use of `MEDIAN()` function before, incorporates the `COUNT()` function to count the number of job schedule types based on given job tite and country.
- **Formula Purpose:** This formula populates the table below, which gives us a list of job schedule types.

#### Background Table

<img src="/Visualizations/type_count_output.png" alt="type_count_output" width="40%" height="40%">


#### Dashboard Implementation:

<img src="/Visualizations/type_count_dashboard.jpg" alt="type_count_dashboard" width="40%" height="40%">



###  Data Validation

####  Filtered List

-  **Enhanced Data Validation:** Implementing the filtered list as a data validation rule under the `Job Title`, `Country`, and `Type` option in the Data tab ensures:
    -  User input is restricted to predefined, validated schedule types
    -  Incorrect or inconsistent entries are prevented
    -  Overall usability of the dashboard is enhanced



## Conclusion
This was my first Excel project ever. From writing that first `=sum()` as a beginner to actually building a full-fledged Dashboard, I was able to execute a lot of the skills I learned before working on this project.

 The Dashboard provides insights into salary trends across various data-related job titles globally, allowing job seekers to make informed decisions about their career paths based on their preferred country of work and and job type.
