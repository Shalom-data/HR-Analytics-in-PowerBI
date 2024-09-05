# Employee Attrition Analysis - Atlas Labs

## Table of Contents 📖

- [Project Overview](#project-overview)
- [Project Objectives](#project-objectives)
- [Methodology](#methodology)
- [Key Pages in this Report](#key-pages-in-this-report)
  - [Overview](#overview)
  - [Demographics](#demographics)
  - [Performance Tracker](#performance-tracker)
  - [Attrition](#attrition)
- [Detailed Insights](#detailed-insights)
- [Actionable Recommendations](#actionable-recommendations)
- [Conclusion](#conclusion)
- [How to View the Report](#how-to-view-the-report)



### Project Overview
This project focuses on exploratory data analysis (EDA) and the use of DAX to build powerful visualizations that will help Atlas Labs understand and address employee attrition. 
- Attrition, or employee turnover, refers to employees leaving the organization, whether voluntarily or involuntarily.

The leadership team at Atlas Labs seeks high-level insights into their workforce, with a particular focus on understanding the factors influencing employee attrition. In addition to attrition analysis, this study also looks into HR metrics related to diversity and inclusion, marital status, and ethnicity. Furthermore, the HR team requested a performance tracking system to continually monitor individual employee performance based on annual performance reviews.


### Tools 🪛

- Excel
- Powerbi


### Project Objectives
The goal of this analysis is to:

1. Identify the factors contributing to employee attrition.
2. Provide a deep dive into employee demographics to identify potential issues related to diversity, inclusion, and other HR metrics.
3. Offer a system to track employee performance over time, enabling managers and HR to monitor and take proactive measures when necessary.


### Methodology
- Step 1: Data Import and Preparation
  - Data Sources: Imported five CSV files related to employee information, attrition, performance, and demographics into Power BI.
  - Fact and Dimension Tables: Labeled and organized the data by creating Fact and Dimension tables to streamline the analysis.
  - Data Formatting: Reviewed the tables to ensure each column was correctly formatted and assigned the appropriate data types.

- Step 2: Date Table Creation
  - Created a Date Table to ensure accurate reporting of date and time-related metrics. This table was used to handle any time-based calculations such as performance reviews and hire/exit dates.
  
- Step 3: Managing Table Relationships
  - Managed relationships between the fact and dimension tables, ensuring that the data is connected properly to allow for seamless cross-referencing in visualizations.

- Step 4: Measures Table
  - Created an empty table to store all measures used throughout the analysis. This allows for cleaner organization of custom calculations, particularly when using DAX to generate insights.
    
    
 
## Key Pages in this Report

### Overview
- An introduction to the report, highlighting the key metrics and providing a high-level summary of employee data.
<img width="595" alt="01_Overview" src="https://github.com/user-attachments/assets/c4526a71-af16-418b-8bc1-e44461ca45b0">


  

### Demographics
- A detailed breakdown of employee demographics, including ethnicity, marital status, and gender representation. This analysis highlights diversity metrics and areas for improvement.
<img width="595" alt="02_Demographics" src="https://github.com/user-attachments/assets/4a78abb9-37a4-4da0-a721-d285f195f347">


  

### Performance Tracker
- A dedicated page to track individual employee performance based on their yearly performance reviews. This allows HR and management to monitor employee growth and identify potential underperformers.
<img width="590" alt="03_Performance tracker" src="https://github.com/user-attachments/assets/87451866-2d45-4694-80c7-1068e03cd47b">


  

### Attrition
- This page displays high-level metrics on attrition rates, identifying key factors that influence turnover. Charts and graphs are used to show trends over time and across different employee demographics.

<img width="590" alt="04_Attrition" src="https://github.com/user-attachments/assets/1204ff0f-982c-43a5-8762-d0fbde6c207b">

  

## Detailed Insights:

- The Technology department is the most populous, reflecting the core nature of Atlas Labs as a software company.

- Software Engineering has the highest number of employees, followed by Data Scientists and Machine Learning Engineers, indicating a strong focus on software development and data-driven initiatives.
  
- The majority of employees hired at Atlas Labs are between 20 and 29 years old, suggesting a young and dynamic workforce.


#### Diversity  & Inclusion Metrics:

- The gender distribution is nearly equal, with females making up **45.92%** and males **44.29%** of the total workforce. This close balance is a positive indicator of gender diversity within the company.
  
- Employees who identify as non-binary account for **8.5%** of the total workforce, showcasing Atlas Labs’ commitment to inclusivity.
  
- Employees who identify as white not only form the majority of the organization but also have the highest average salary. Conversely, employees who identify as mixed or multiple ethnic groups have one of  the lowest average salaries, highlighting a potential area for review and improvement in pay equity.
  

#### Attrition Insights:

- Employees considered as frequent travelers have the highest attrition rate despite only making up **19%** of the total workforce, indicating that frequent travel may contribute to turnover.
  
- Employees who worked overtime had an attrition rate of **30.5%**, compared to their counterparts with an attrition rate of **10.5%**. This suggests that excessive overtime may lead to higher turnover.
  
-  A significant % attrition rate of **25%** was recorded in 2020, possibly due to external factors such as the global pandemic, warranting further investigation.
  
-  Sales representatives had the highest attrition rate at **39.8%**, indicating a need to address retention strategies in this department.
  
-  Employees who had only spent one year with the company had an attrition rate of 34.5%, suggesting that early-stage employee engagement and support may need improvement.



 ### Actionable Recommendations
 
1. Address the high attrition rates among specific groups such as frequent travelers, overtime workers, and sales representatives. Consider implementing tailored retention strategies like flexible work arrangements, workload management, and targeted employee engagement programs.
   
2. Investigate the challenges faced by frequent travelers and consider offering additional support or incentives to reduce attrition in this group, such as flexible travel arrangements or work-from-home options.
   
3. Review the salary structures to ensure equitable compensation across all ethnic groups and gender identities. Conduct a pay equity audit to identify and address any disparities.
   
4. Enhance onboarding and mentorship programs to better support employees in their first year, which may reduce the high attrition rate among this group.
   
5. Investigate the challenges faced by sales representatives and consider strategies to improve job satisfaction and retention in this high-turnover group.
   
6. Further analysis is recommended to identify the factors contributing to the high attrition rate in 2020 and develop strategies to mitigate similar risks in the future, such as improved crisis management and employee support systems.
    
7. Lastly, given the large concentration of employees in Software Engineering, Data Science, and Machine Learning, it may be beneficial to invest in ongoing training and development programs to maintain and enhance the technical skills of these teams.

## Conclusion
This analysis helps Atlas Labs gain visibility into the key drivers of employee attrition and provides actionable insights into workforce diversity and performance management. By implementing these findings, Atlas Labs can take proactive steps to improve employee retention and foster a more inclusive workplace.

## How to View the Report
To view the full interactive report, download the .pbix file and open it in Power BI Desktop. If you do not have Power BI Desktop, you can view the screenshots and exported visuals included in this repository.

### Thanks for your time👍



