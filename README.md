# Analysis of employee attrition

## Table of Content

- [Project Overview](project_overview)

- [Data Source](data_source)

- [Tools](tools)

- [Data Cleaning/Preparation](data_cleaning/preparation)

- [Exploratory Data Analysis](exploratory_data_analysis)

- [Data Analysis](data_analysis)

- [Results/Findings](results/findings)

- [Recommendations](recommendations)

- [References](references)

 


### Project Overview

This data analysis project aims to provide insight into a company's employee attrition over a particular period. By analyzing the employee attrition data, I seek to identify trends and make insightful recommendations.


### Data Source

Employee Attrition data: The primary dataset used for this analysis is the employee_attrition.xlsx file, which contains detailed information about the company's employee attrition rate.


### Tools

Excel is the source of the dataset.
Power BI is used to clean the dataset, format, transform, group, and create the dashboard.


### Data Cleaning/Preparation

In the initial data preparation stage, I performed the following tasks:
• Deleting redundant columns.
• Renaming the columns.
• Dropping duplicates.
• Cleaning individual columns.
• Remove the NaN values from the dataset
• Check for some more Transformations


### Exploratory Data Analysis

EDA involved exploring the employee attrition data to answer key questions such as:
What is the total number of attrition?
What is the percentage of attrition based on gender and age group?
What are the top contributing factors to the attrition?


### Data Analysis

-I downloaded the dataset and uploaded the data using the "Get Data" option in 
Power BI. Then, I utilized the "Transform" option to check for any null values 
in the dataset
-Using the "Format Visual" option, I customized the design of the cards as 
needed
-Navigate to the table view, click "New Column," and apply the provided
formula:
~~~Power bi
Attrition Count = switch(true(), 'HR-Employee-Attrition'[Attrition] = "Yes", 1, 'HR-Employee-Attrition'[Attrition] = "No",0,0)
~~~
-Summing all the 1s gives the total attrition count that is 237
-Subtracting this from the employee count yields the count of active
employees that are 1233
-Using grouping for some columns to give categories
-Combining different categories with count of attrition to give a visualized report
-Visuals used include cards, stacked bar charts, column charts, clustered bar charts, pie charts, tables, and donut charts.


### Results/Findings

The analysis results are summarized as follows
1. The company has experienced a 16% attrition over time with a total of 233 employees
2. Male employees have the higher percentage of attrition with 63% while females have 37%
3. Employees in the life sciences educational field have the highest attrition
4. the highest attrition by age group is 30-40 years
5. Single males and females have the highest attrition
6. The department with the highest number of attrition is sales with 92%
7. Employees with less than 1year in their current role have the highest attrition
8. Overtime contributes largely to employee attrition
9. The job level with the highest attrition is entry-level
10. Very dissatisfied employees with the work environment have the highest attrition


### Recommendations

     Based on the analysis, I recommend the following actions:
   . More attention should be given to employees with life sciences education background as they have the highest number of attrition
   . More attention should also be given to employees between between ages of 30 and 40 by checking their job satisfaction level on a time interval
   . Ensure that the single males and females in the company are enjoying a good work environment
   . Special attention should be given to employees in sales and maybe introduce bonuses for higher sales as this will increase performance rating and reduce attrition
   . Entry-level employees and employees in less than 1 year in their current job role should be a lot of support with their tasks as it will help them stay much longer
   . Employees should not be made to have overtime or be compensated for any necessary overtime
   . Generally make the work environment satisfactory for all employees as very dissatisfied employees have the highest attrition


### References
1. [ChatGPT](ChatGPT.com)



