# DATA PROFESSIONAL'S SURVEY 



![students-feedback-survey-cvr](https://github.com/Shreya007data/Data-Professionals-Survey-Dashboard-/assets/132162991/42436097-ad6a-4b80-9bab-620834dd88f9)


## OVERVIEW
 Welcome to my Data Professionals Survey Dashboard! This  [Power BI ](https://app.powerbi.com/groups/me/reports/16c1e23f-2927-4ef6-909d-490c13b31438/ReportSection?experience=power-bi)  creation showcases the rich insights obtained from a comprehensive survey conducted by Alex The Analyst of data professionals around the globe.
 
 ## METHODOLOGY
 * The survey data was cleaned using the Power Query Editor, and a Power BI dashboard was created to visualize the data. 
 * This Power BI dashboard includes various charts and graphs that showcase and highlights crucial aspects of data geeks such as popular tools and technologies, preferred programming languages, average salaries, job satisfaction levels and many more.

## TOOLS USED
 * Microsoft Excel 
*  Power BI

##  STEPS TAKEN

### 1- Getting Dataset
The Dataset of the survey is available as an Excel file in this repository. You can also download the dataset from this [link ](https://docs.google.com/spreadsheets/d/1hbMiWzfDxzqX0xhULse72Vdvx7FnnfJL/edit?usp=sharing&ouid=114196969390185685049&rtpof=true&sd=true).


### 2-  Data Cleaning: Power Query
In this process, I have done data cleaning and transformation using **Power Query** - 

- Firstly, I removed columns that were not relevant for the analysis like Browser, OS, city etc.
  
- The  Job Title and Favourite Programming Language column includes many other values that are not useful to us. So, we used **Split Column** and grouped every other value under Others category to achieve the below mentioned list:

 
![Screenshot 2023-07-30 224321](https://github.com/Shreya007data/Data-Professionals-Survey-Dashboard-/assets/132162991/c9602e32-b9a2-4156-906f-d974c139d25a)


![Screenshot 2023-07-30 224354](https://github.com/Shreya007data/Data-Professionals-Survey-Dashboard-/assets/132162991/6c427c45-8d30-4567-9d08-5c94828544b6)




- The salary column had ranges provided in it which too in text format, I needed a numerical value for our analysis so firstly I used the split column to divide columns with lower and upper values in each. Then, I used the **Custom Column** to calculate the  average salary, it is more usable now  & the results are below:


![Screenshot 2023-07-30 224831](https://github.com/Shreya007data/Data-Professionals-Survey-Dashboard-/assets/132162991/a2b1069a-dce9-486d-b1b6-ac377c24f232)


### 3-  Dashboard Overview
The Parameters used for Data Visualization are - 
1.  **Country of Respondents**
2. **Career Transition**
3.  **Average Salary by Job Title**
4.  **Total Count of Survey Takers**
5.  **Average Age of Survey Takers**
6.  **Work / Life Balance situation**  
7.  **Favorite Programming Languages**
8.  **Difficulty to Break in Data**  
9.  **Average Happiness with Salary**
10. **What Percentage of People Working in Different Industry** 

###  4- Data Visualisation

![DASHBOARD SS NEW](https://github.com/Shreya007data/Data-Professionals-Survey-Dashboard-/assets/132162991/38530607-0e06-4918-a383-13ad68f56d8e)

## KEY FINDINGS
1. A total of **630** data geeks around the globe participated in the survey with the average age of survey takers being **29.87 years**, providing a significant sample size.  
2. Data professionals are quite satisfied with their work-life balance but not with their salaries.  
3. **Data scientists earn higher salaries** on average than data engineers, data analysts, and other professionals in the field.  
4. **Python** is the most popular programming language among data professionals, followed by R. 
5.  Out of the total Survey takers **372** people have transitioned into the Data domain which is almost **60%** of people working as Data Professionals out of them **39.52 %** believed it is neither too difficult nor too easy to transition.

