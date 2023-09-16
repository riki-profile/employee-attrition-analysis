# Employee Attrition Analysis
---

## Tableau Dashboard Link
- [Click Here to View the Tableau Dashboard](https://public.tableau.com/views/employee_attrition_dashboard/Home?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

## 1. Background

In today's dynamic and competitive business landscape, employee attrition has emerged as a significant concern for organizations worldwide. Employee attrition, often referred to as employee turnover, is the phenomenon of employees leaving an organization and needing to be replaced. This phenomenon can have far-reaching consequences on an organization's performance, productivity, and overall success. Identifying the underlying factors that contribute to employee attrition and developing effective strategies to manage it are crucial steps for any business aiming to maintain a talented and motivated workforce.

## 2. Problem Statement

The purpose of this analysis is to identify the main factors that contribute to the level of employee attrition in the company. By understanding these factors, strategic steps can be taken to decrease the employee turnover and maintain workforce stability.

## 3. Problem Statement Exploration
- How much is the employee attrition rate who left the company?
- What is the profile of employees more likely to leave the company?
- How long is the average duration of the employee's stay at the company? What is the range?
- What factors are dependent on the turnover decision?
- And more.

## Data Loading

- Data source: 
    - HR Analytics Case Study from Kaggle  [(*Click Here!*)](https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study)
    - or copy the link : https://www.kaggle.com/datasets/vjchoudhary7/hr-analytics-case-study
- There are 3 Tables with columns details :

| Column Name   | Description                                 | Details                           |
|---------------|---------------------------------------------|-----------------------------------|
| Age           | Age of the employee                         |                                    |
| Attrition      | Whether the employee left in the previous year or not       |         |
| BusinessTravel      | How frequently the employees travelled for business purposes in the last year        |            |
| Department           | Department in company         |              |
| DistanceFromHome  | Distance from home in kms         |            |
| Education   | Education Level             | 1:'Below College', 2:'College', 3:'Bachelor', 4:'Master', 5:'Doctor'     |
| EducationField  | Field of education         |          |
| EmployeeCount | Employee count | |
|EmployeeNumber | Employee number/id|  |
| EnvironmentSatisfaction | Work Environment Satisfaction Level | 1:'Low', 2:'Medium', 3:'High', 4:'Very High'|
| Gender | Gender of employee |   |
| JobInvolvement | Job Involvement Level | 1:'Low', 2:'Medium', 3:'High', 4:'Very High'|
| JobLevel | Job level at company on a scale of 1 to 5 |   |
| JobRole | Name of job role in company |   |
| JobSatisfaction | Job Satisfaction Level | 1:'Low', 2:'Medium', 3:'High', 4:'Very High'|
| MaritalStatus | Marital status of the employee |  |
| MonthlyIncome | Monthly income in rupees per month |  |
| NumCompaniesWorked | Total number of companies the employee has worked for |  |
| Over18 | Whether the employee is above 18 years of age or not |  |
| PercentSalaryHike |Percent salary hike for last year |  |
| PerformanceRating | Performance rating for last year | 1:'Low', 2:'Good', 3:'Excellent', 4:'Outstanding' |
| StandardHours | Standard hours of work for the employee |   |
| StockOptionLevel | Stock option level of the employee  |   |
| TotalWorkingYears | Total number of years the employee has worked so far |  |
| TrainingTimesLastYear | Number of times training was conducted for this employee last year |  |
| WorkLifeBalance | Work life balance level | 1:'Bad', 2:'Good', 3:'Better', 4:'Best'|
| YearsAtCompany | Total number of years spent at the company by the employee |  |
| YearsSinceLastPromotion | Number of years since last promotion |   |
| YearsWithCurrManager | Number of years under current manager  |   |

### Conclusion and Recommendation

#### Conclusion

In this exploratory data analysis, it is observed that approximately 16.1% of employees have resigned from the company. The analysis has enabled the identification of certain employee characteristics that are associated with attrition. Most of the employees who left are males aged between 25 to 35 years, and they are predominantly single. The Research and Development department is the most affected by attrition, and a majority of the departing employees possess a bachelor's degree, particularly with a background in Life Science.

The job satisfaction analysis presents an intriguing insight. Despite common assumptions, a significant proportion of employees who left the company (attrition 'Yes') had expressed a high level of job satisfaction. This finding indicates that attrition is influenced by factors beyond job satisfaction alone. However, the analysis also reveals that the 'low' job satisfaction category ranks second highest, suggesting that dissatisfaction could still contribute to attrition.

The histogram depicting the distribution of total working years for departing employees shows a right-skewed shape, indicating that the data is not normally distributed. Most of the distribution is concentrated below 10 years of employment duration, with a declining trend as experience increases. While the visualization portrays this trend, a descriptive statistical analysis of the average working years indicates an average experience of around 5 years. Moreover, based on a confidence interval, it can be reasonably concluded that the average duration of employment for the population falls within the range of 4.6 - 5.5 years, considering the sample data.

An inferential statistical approach was also employed to determine the factors associated with attrition. The analysis revealed that 17 factors exhibit a statistically significant relationship with attrition, while 9 factors appeared to be independent. However, the current analysis does not offer insights into the direction of these correlations. Subsequent analyses will be conducted to explore the direction and strength of the relationships between the identified factors and attrition, providing a more comprehensive understanding of their impact.

#### Recommendation

Here are some recommended follow-up actions based on the insights obtained:

1. **Focus on Reducing Attrition in R&D Department**: Currently, the resignation rate is around 16%, with a significant proportion coming from the Research and Development (R&D) department. The company should pay special attention to this department and implement strategies to address the underlying reasons for attrition, possibly through improved work conditions, growth opportunities, or addressing concerns specific to this department.

2. **Employee Engagement and Recognition Program**: The HR department could consider introducing programs or initiatives to recognize and appreciate employees who have remained with the company for more than 4 years. The insights indicate that there's a trend of attrition around the 4.6 - 5.5 years mark of working experience. By implementing appreciation programs, the company can foster a sense of belonging and engagement, encouraging employees to stay beyond this critical period.

3. **Deeper Analysis for Comprehensive Understanding**: Analysts should conduct a more detailed analysis to uncover deeper insights into the factors influencing attrition. This could involve examining factors such as work-life balance, compensation, career growth, and organizational culture. Understanding these underlying factors can help the company tailor its strategies more effectively to mitigate attrition.

By taking these actions, the company can not only address the immediate attrition concerns but also create a more engaging and supportive work environment that encourages employee retention and enhances overall organizational success.

