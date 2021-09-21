# Employee-Performance-Analysis
Project Summary
PROJECT Code: 10281 Employee Performance Analysis INX Future Inc.

Requirement
Employee Performance Analysis

INX Future Inc, is one of the leading data analytics and automation solutions provider with over 15 years of global business presence. INX is consistently rated as top 20 best employers past 5 years. In recent years, the employee performance indexes are not healthy and this has become a growing concern among the top management. CEO, Mr. Brain, knows the issues but concerned to take any actions in penalizing non-performing employees as this would affect the employee morale of all the employees in general and may further reduce the performance. The CEO Mr. Brain, decided to initiate a data science project, which analyzes the current employee data and find the core underlying causes of the performance issues. He also expects a clear indicators of non-performing employees, so that any penalization of non-performing employee, if required, may not significantly affect other employee morals.

The following requirements that are expected from this project:

Department wise performances.
Top 3 Important Factors effecting employee performance.
A trained model which can predict the employee performance based on factors as inputs.
Recommendations to improve the employee performance based on insights from analysis.
Analysis
The given data of employees has the 1200 rows to model in machine learning where it is well structured. The Shape of the data is 1200x28. Where 16 features are qualitative and 11 features are quantitative. The employee ID data doesn't play a role as a relevant feature for performance rating.

The data is supervised and categorical. The predictor variables are ordinal and a few among them are nominal. The target variable 'Performance Rating' is ordinal.

Import the data provided, find out the predictor & target variables and look for missing values.

Analysis of Department wise performance as asked.

Label Encoding the ordinal columns.

Calculate correlation coeffecient to find out the relationship between variables and then select the important features for analysis.

Standardizing the data and splitting it into test and train.

For training the data and predicting the target, algorithms used are Logistic Regression, Decision Tree, Random Forest, XGBoost Classifier and checking the accuracy to find out which algorithm is the best.

Exporting the model with highest accuracy.

(i) Analysis by the distribution of the data
-The age distribution is starting from 18 to 60 where the most of the employees are lying between 30 to 40 age count.

-The distance from home to office is distributing from 0 unit to 30 unit which can be kilometre or mile. The most of the employees are coming from the range of 0 to 5 units.

-Employees are worked in the multiple companies up to 8 companies where most of the employees worked up to 2 companies before getting to work here.

-The hourly rate range is 65 to 95 for majority employees work in this company.

-In General, Most of Employees work up to 5 years in this company.

-Most of the employees get 11% to 15% of salary hike in this company.

-The Gender variance is divided by 60% of Male employees and 40% of Female employees in the company.

-The number of the educational backgrounds present in the employees is six unique backgrounds.

-nineteen unique employee job roles are present in this company.

-The most of the employees are having the education level of 3

-The Job satisfaction level in this company is high level for the majority of employees.

-The 85% of employees are not having attrition in their work.

-only 11% of employees in the company were achieved level 4 - performance rating.

-The overall percentage of employees doing overtime is 30%.

Features like EmpEnvironmentSatisfaction, EmpLastSalaryHikePercent, EmpWorkLifeBalance has high positive correlation wih the target. OverTime, MaritalStatus, NumCompaniesWorked, EmpEducationLevel, EducationBackground, EmpJobSatisfaction has moderate positive correlation with the target.

(ii ) Analysis by the visualization
On average rating of each department analysis we got to know some insights as follows Development and Data Science Departments have highest overall performance ratings compare to all other departments. And No department is performace is least , all departments are doing well.

From each department ratings plot

-More number of employees in sales department are having poor performances comparatively, sales has the quite good number of average performers too.

-Human Resources have more number of rating 2 than the number of 4 ratings but the moderate performers (rating 3) is quite high.

-Highest average performance(rating 3) is in development team with quite high number of good performances(rating 4) and very few low poor performances.

-There are average performers and few best performers in data science with negligible worst performances.

-Research and development has the second most worst performances with quite few best performances and huge moderate performances (rating 3).

-Finance has very few best (rating 4), more number of moderate performances, and noctiable amount of low performances.

Top three factors affecting the performance :

Here We can observe that, factors that are negatively correlated and positevely correlated. and Top 3 factors which affect the employee performance are

Employee EnvironmentSatisfaction,
Employee Last Salary Hike Percent and
EmpWorkLifeBalance
-The most important features selected are EmpEnvironmentSatisfaction, EmpLastSalaryHikePercent, EmpWorkLifeBalance, OverTime, MaritalStatus, NumCompaniesWorked, EmpEducationLevel, EducationBackground, EmpJobSatisfaction.

Model with the results(accuracy)

-Logistic Regression - 79.66 %

-Decision Tree - 86.33 %

-Random forest classifier - 93 %

-XG Boost - 92 %

For this project, we used algorithms like Logistic Regression, Decision Tree, Random Forest to calculate the accuracy and found out that Random Forest gives the maximum accuracy of 93%.

Recommendations
From the analysis we found out that, The Variables like Employee EnvironmentSatisfaction, EmpLastSalaryHikePercent, EmpWorkLifeBalance, ExperienceYearsInCurrentRole, OverTime are more related to the performance ratings, So company need to focus on.

We can conclude that the company should provide a better environment as it increases the performance drastically. The company should increase the salary of the employee from time to time and help them maintain a worklife balance.

