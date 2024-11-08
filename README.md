# HR-Data
This Analysis is to know the Attrition rate of an organization, the department with high attrition rate and the likely cause of leaving the organization

### Project Topic: Attrition Rate

[Project Overview](#project-overview)

[Tools Used](#tools-Used)

[Data Cleaning and Preparations](#data-cleaning-and-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

 [Data Visualization](#data-visualization)

---
### Project Overview:
---
This analysis explores the factors contributing to employee attrition within an organization by examining a dataset that includes demographic information, job-related attributes, and measures of job satisfaction. The primary objectives are to identify trends and patterns linked to attrition, assess the impact of job satisfaction, compensation, and career advancement on employees' decisions to leave, and create a predictive model to anticipate attrition. The insights gained from this analysis will facilitate data-driven decision-making for employee retention, ultimately assisting the organization in reducing turnover costs and fostering a more dedicated workforce. Additionally, we will uncover the dynamics that lead to employee attrition, which will enable the organization to enhance retention strategies.


### Data Sources 
---
The main data source utilized in this analysis is a HR.Data.csv file, an open-source dataset that can be freely downloaded from various online platforms.

### Tools Used
---
- Power BI
   - for Data Cleaning, Analysis and Visualization 
- GitHub for Portfolio Building

### Data Cleaning and Preparations 
---
In the initial phase of the Data cleaning and Preparations, we perform the following actions;
- Data loading and Inspection:
    - The dataset was imported from excel into PowerBI 
- Handling missing Variables:
    - Promoted headers; this means the first row of the data was used as column hearders
- Data Cleaning and Formatting:
    - Creation of new column:
       1. Created a conditional column to classify age brackets (Age_Band)
       2. Created a conditional column for Job Satisfaction Ratings
- Sorted a Visual:
        - Created a conditional column to sort Column (Age_Band); Age_band was sorted by the new column created so that it will be arranged in ascending order in the visuals 


### Exploratory Data Analysis
---
EDA involves exploring of the data to answer some questions about the Data such as;
 - What is the overall Attrition Percentage
 - Which department have the highest attrition rate  
 - What is the Attrition count by Educational Field 

### Data Analysis 
---
This is where we include basic insights gained during analysis
 - The total number of employees is 1470
 - Total number of current employees is 1233
 - Total number of attritions is 237
 - Attrition rate is 16%
 - Average Age is 37

### Data Visualization
---

![HR Data](https://github.com/user-attachments/assets/dbacc80d-88f6-4a4d-bcb7-d0e76cee3226)

### Report 
---

- Attrition By Education Field

Attrition by Education Field reveals the following trends:

i. The Life Sciences field has the highest attrition count, with Medical and Marketing fields following closely behind.

ii. In contrast, fields such as Technical Degree and other specialties exhibit relatively lower attrition rates.

- Attrition By Department 

i. Attrition shows considerable variation across different departments.

ii. The R&D department experiences the highest level of attrition, with 961 employees having left.

iii. Following that, the Sales department has seen 446 employees depart.

iv. Conversely, the HR department reports the lowest attrition rate, with only 63 employees leaving.

- Attrition by Gender
  
  Attrition by Gender indicates that:

i. A significant majority of the attrition, accounting for 63.29%, involves male employees (150), while female employees represent 36.71% (87) of the attrition cases.

When looking at Attrition by Gender and Age Band:

i. The breakdown reveals that the 25-34 age band has the highest attrition, with 122 employees.

### Recommendations
---

1. Retention Analysis: To tackle the high attrition in R&D and Sales, we should conduct detailed exit interviews to gather qualitative data on the reasons behind employee departures. By analyzing this information, we can identify common themes and develop targeted retention strategies to address the root causes.

2. Field-Specific Insights: In the Life Sciences and Medical sectors, enhancing job satisfaction is crucial. By analyzing metrics like customer satisfaction scores and retention rates, we can gain valuable insights into employee sentiment and areas for improvement. Implementing tailored programs based on this data can help boost engagement and retention in these key fields.

3. Continuous Monitoring: It's essential to establish a robust data monitoring system to track attrition trends over time. By regularly evaluating metrics such as customer satisfaction scores and Net Promoter Score, we can proactively identify shifts in employee retention and adjust our strategies accordingly.

By leveraging data analysis techniques in these areas, we can gain valuable insights that drive informed decision-making and ultimately improve employee retention rates 



