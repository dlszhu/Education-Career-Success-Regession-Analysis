# How Education Could Affect Career Success

### Project Summary and Introduction
In this project, we evaluate the impact of education on career success using salary as a proxy. Specifically, we research how the relevancy of one's education field and education level affect their salary. 

"Salary" (Monthly Income) is used as our dependent variable as a proxy of workplace success and progression. 

"Education" being our independent variable, is evaluated from two main perspectives. The first one being the education level's impact on career success. Would a graduate degree result in a higher average salary? Secondly, we look at the relevancy of education background or field with the employee's job role. Would having an education in a relevant field yield a better salary?

### Why is this Question/Analysis Important?
Education is commonly considered as a key factor when determining the personal attainment of a candidate or employee. Job roles typically prefer or even require specific education levels or fields of study, yet we lack empirical evidence to understand the true impact education has on career success.

### Potential Business Implications
Gaining insight into this topic could potentially be very valuable especially from a Human Resources standpoint. Having a data driven approach to guide hiring and employee promotion decisions could mean better prospects and career progression for an employee within a company.

A more streamlined allocation of budget that accounts for the different impacts that an employee's education background has on each functional role in a company could ensure employees with higher relevant skillsets and productivity are rewarded accordingly.

A possible benefit from these would mean lower attrition rates, as employees might have a higher motivation to leave when they are not paid adequately or feel stagnated in their career paths. With lower attrition rates, a company could reduce wastage on the expensive process of onboarding and training.

### About the Dataset
Source : [Dataset Link](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset)

We chose to go with a single dataset by IBM that contains information on employee satisfaction, income, seniority, and demographics like age and education background. It includes data for 1,470 employees.

Of the 35 columns, we use the following:
| Column      | Description |
| ----------- | ----------- |
| MonthlyIncome       | The monthly salary for the employee, which is used as the gauge for career success.       |
| Gender              | Whether the employee is Male or Female.        |
| JobRole             | The name of the role held by the employee, which we use to determine the relevant field.        |
| Department          | The department the employee works in, which we use to group employees and also to determine a manager's relevant field.        |
| Education           | The employee's education level, from Level 1 to 5, including Below College, College, Bachelor, Master, Doctorate.        |
| EducationField      | The field that the employee received education in, including Human Resources, Life Sciences, Marketing, Medical Sciences, Others, and Technical.|
| TotalWorkingYears   | The total number of years worked.|



### Key Takeaways

#### Summary of the overall impact of education level and relevance of education field
<ul>
  <li>A higher education level does not necessarily link to a higher salary, as we merely observed one positive correlation with senior level employees and this is better explained by how education becomes a key differentiator in deciding salary for this level. Furthermore, junior-level employees with a doctorate degree have a higher average salary. Ultimately, this could be due to the small sample size of employees with a PhD, which amplifies the effect of an advanced academic degree.</li>
  <li>Having a relevant education background makes sense when it comes to explaining the salary of R&D employees. The technical and specialized roles within this department generally require expertise within their field. </li>
  <li>On the contrary, HR and Sales place more value on work experience, as total working years are more significant predictors of salary. This could be due to the less technical nature of these roles that benefit more from having more years of practical experience.</li>
</ul>

#### Does it confirm or challenge our previous belief?
<ul>
    <li>Challenge : Education is not a significant predictor of salary.</li>
</ul>

#### Business Implications of the findings
<ul>
  <li>The impact of education on salary should consider how work experience has a more significant impact on salary along with how different functions of work value education differently.</li>
  <li>When making hiring or job promotion decisions, companies should weigh education differently in the evaluation of candidates or employees based on the specific needs of their roles.</li>
</ul>

#### Potential Improvements
<ul>
  <li>Aside from the academic attainments of the employees, on-job training has been a crucial factor linked to workplace success measured in salary. This dataset fails to provide insight of the total training time of employees, having only the previous year's training information.</li>
  <li>A candid performance rating system could be a good control variable that increases the total statistical significance of the model and accounts for the uninterpreted variation. However, the performance rating in this dataset lacks depth with only either "Good" or "Outstanding".</li>
  <li>Some employees could have entered the company with matching previous job experience that this dataset does not account for. This could be a factor that leads to a higher salary even with a mismatched education background. It is entirely possible that one has gained skills necessary for their new role from their work experience instead of school.</li>
  <li>The sample size is also fairly limited.</li>
</ul>
