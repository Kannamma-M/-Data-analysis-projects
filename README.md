**POST-PANDEMIC REMOTE WORK MENTAL HEALTH IMPACT ANALYSIS**

**Project Overview**

This project analyses the post-pandemic remote work's mental health impact (2025), focusing on work mode impact on the employee's mental health across various working conditions.

Data cleaning and pre-processing are done in Excel and data visualization is done using PowerBI.

**Project Objectives**

Analysing the remote work impacts on mental health of employees based on categories such as working hours per week, work life balance, social isolation score on various aspects of employees such as work mode, gender, role type, industry type and regions. In addition, both the hybrid and on-site working modes are also compared.

**Data Source**

Kaggle (2025)

**Domain**

Human resources

**Dataset used**

Downloaded the "post_pandemic_remote_work_health_impact_2025" dataset file from Kaggle.

**Dataset Column Details**

Survey_Date, Age, Gender, Region, Industry, Job_Role, Work_Arrangement, Hours_Per_week, Mental_Health_Status, Burnout_Level, Work_Life_Balance_Score, Social_Isolation_Score, Salary_Range.

**Numerical data**

Survey_Date, Age, Gender,Region, Hours_Per_week, Work_Life_Balance_Score, Social_Isolation_Score, Salary_Range.

**Categorical data**

Gender, Region, Industry, Job_role, Work_Arrangement, Hours_Per_week, Mental_Health_Status.

**Data Cleaning and Pre-processing**

Data Cleaning and Pre-processing is done in Excel

- Standardised the header size according to the data
- Checked for duplicates
- Checked for missed values and filled the single missing date value in the last date column,
- Checked for spellings, proper cases, and corrected the appropriate ones like changing "remote to Remote", "PTsD to PTSD", high and medium to "High", "Medium".
- All the columns are filtered and sorted.

**Data analysis and Data Visualization**

Created a new conditional column to convert the salary ranges into salary grades.

Developed interactive PowerBI dashboard addressing all the objectives using:

- Cards
- Bar Graphs
- Column Charts
- Pie Charts
- Maps
- Report insights

**Cards**

Developed card views to analyse averages of age, Social_isolation_Score, Hours_Per_week, Work_Life_Balance_Score and for the gender count.

**Column Chart:**

- Column Chart for comparing Sum of Hours_Per_week by Salary Grade and Burnout_Level.
- Column Chart2 to compare number of Gender by Mental_Health_Status and Gender types.
- Column Chart3 to compare number of Gender by Mental_Health_Status and Work_Arrangement.

Created a **Map** Visual to show Social_Isolation_Score by Region.

**Pie Charts**

Compared Hours_Per_week by Industry, Work_Life_Balance_Score by Work_Arrangement and Gender

**Dashboard:**
![](https://github.com/Kannamma-M/-Data-analysis-projects/blob/main/Dashboard%20Screenshot.png)

**Summary Metrics:**

Gender Count: 3157

Average Age: 43.73

Average Social Isolation Score: 2.70

Average Weekly Working Hours: 49.90

Average Work-Life Balance Score: 3.00

**Insights:**

- **Professional Services** category employees have the highest working time of all the other Industrial Categories.
- **Grade3** employees have the highest in the high level burn out score levels and medium level burn out score levels
- **Grade4** employees have the long working hours per week.
- **PTSD and depression** appear most common across male and female employees
- **Remote workers** show fewer mental issues than onsite and hybrid workers
- **South America** workers show high social isolation levels
- **Onsite workers** work more time than hybrid and remote.
- **On-site** has the highest work-life balance score.
- **Onsite workers** show more mental illness and social isolation levels

**Conclusion**

The integration of Excel and PowerBI enabled a comprehensive analysis of the workers mental health

based on several factors.

- Remote workers have good work-life balance but also most affected by long working hours and suffer most of the mental illness.

This project transformed complex employee data into **clear, actionable insights** on post pandemic remote workers mental health as well as Onsite and hybrid workers mental health.
