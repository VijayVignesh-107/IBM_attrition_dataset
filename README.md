# IBM_attrition_dataset

Hi,

As part of my dataset journey, i have now selected the IBM HR attrition dataset to built an datamodel for prediction. This dataset has 35 columns which gives different aspect of the employee that determines or possible causes of the attrition.

# Column explanation:

Age	: This column gives us the age of the employee. We will be able to analyse that employee of which age group resigns from the organization mostly.
Attrition	: This column lets us know whether the employee has resigned from the organization or not.
BusinessTravel: This column gives us the detail about the travel history of the employee for the business.
DailyRate: This column gives us the daily rate(wage) of the particluar employee.
Department: This column let us know in which department the user is currently working in the organsation.
DistanceFromHome: This column let us know the distance betwwen the employee home and the office.
Education: This column gives us the level of education of the particular employee. This is a category based column which gives the values as (1 'Below College',2 'College',3 'Bachelor',4 'Master',5 'Doctor')
EducationField: This column gives us the field of education in which the user has studied education.
EmployeeCount: This column gives us the count of the employee matched for the particular count.
EmployeeNumber: This column gives us the employeenumber (unique num) for the eplyee in the organisation.
EnvironmentSatisfaction: This column gives us the satisfaction rate of the employee in the office environment. This is a category based column which gives the values as (1 'Low',2 'Medium',3 'High',4 'Very High')
Gender: This column gives us the gender of the employee.
HourlyRate: This column gives us the hourly rate(wage) of the particluar employee billed from.
JobInvolvement: This column gives us the job involvement rate of the employee in the office environment. This is a category based column which gives the values as (1 'Low',2 'Medium',3 'High',4 'Very High')
JobLevel: This column gives us the Job level(hierarchy) of the employeein the organization.
JobRole: This column gives us the what is job role or title of the employee in the organization.
JobSatisfaction: This column gives us the job Satisfaction rate of the employee in the office environment. This is a category based column which gives the values as (1 'Low',2 'Medium',3 'High',4 'Very High')
MaritalStatus: This column gives us the marital status of the employee
MonthlyIncome: This column gives us the monthly income value of the employee.
MonthlyRate: This column gives us the monthly rate(wage) of the particluar employee.
NumCompaniesWorked: This column gives us the number of companies the employee has worked previously.
Over18: This column confirms whether the employee is above over 18 or not.
OverTime: This column gives us the whether the employee has worked overtime or not for the organisation.
PercentSalaryHike: This column gives us the Percentage of the salary hike, of the employee received in last year.
PerformanceRating: This column gives us the performance rating of the employee for the past year.
RelationshipSatisfaction:  This column gives us the Relationship Satisfaction of the employee in this personal life. This is a category based column which gives the values as (1 'Low',2 'Medium',3 'High',4 'Very High')
StandardHours: This column gives us the standard working hours of the employee in the organisation.
StockOptionLevel: This column gives us the stock level option of the employee in the organisation.
TotalWorkingYears: This column gives us the total working experience of the employee.
TrainingTimesLastYear: This column gives us the value of the training sessions that the employee attended last year.
WorkLifeBalance: This column gives us the rating of the work life balance of the employee. This is a category based column which gives the values as (1 'Bad',2 'Good',3 'Better',4 'Best')
YearsAtCompany: This column gives us the number of years, the employee is working the company.
YearsInCurrentRole: This column gives us the number of years, the employee is working in their current role.
YearsSinceLastPromotion: This column gives us the number of years, the employee has got their last promotion.
YearsWithCurrManager: This column gives us the number of years, the employee is working under the current manager.

# Dependent/Independent columns

In the dataset, we have dependent and independent column. Independent columns are the ones which do not influence the other column based on its value. depndent columns are the ones in which the values are dependent on the values of other columns. PFA the dependent/independent columns presernt in the dataset.

# Dependent columns: attrition

# Independent columns: All other columns are independent columns.

Supervised Learning:
This dataset is based on Supervised Learning. By calculating the independent columns, how they influence the dependent column. The model i'm trying to develop, is by using the independent column values, to predicthow likely the employee will resign from the current job.

