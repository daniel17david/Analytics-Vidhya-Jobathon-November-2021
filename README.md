# Analytics-Vidhya-Jobathon-November-2021

The largest Data Science Hiring Event is Back!
And this event is your one shot at scoring your dream job.

Analytics Vidhya presents “JOB-A-THON” - India's Largest Data Science Hiring Event, where 1600+ of candidates have interviewed for over 65+ companies. You could be among them too! 

At JOB-A-THON every enthusiast will get the opportunity to showcase their skills and get a chance to interview with top companies for leading job roles in Data Science, Machine Learning & Analytics. 


**RANK:** 29 out of 7677

**SCORE:** 0.7214379823

![rank](rank.png)

## Problem Statement:
In recent years, attention has increasingly been paid to human resources (HR), since worker quality and skills represent a growth factor and a real competitive advantage for companies. After proving its mettle in sales and marketing, artificial intelligence is also becoming central to employee-related decisions within HR management. Organizational growth largely depends on staff retention. Losing employees frequently impacts the morale of the organization and hiring new employees is more expensive than retaining existing ones.

You are working as a data scientist with HR Department of a large insurance company focused on sales team attrition. Insurance sales teams help insurance companies generate new business by contacting potential customers and selling one or more types of insurance. The department generally sees high attrition and thus staffing becomes a crucial aspect.

To aid staffing, you are provided with the monthly information for a segment of employees for 2016 and 2017 and tasked to predict whether a current employee will be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 2018) or not, given:

* Demographics of the employee (city, age, gender etc.)
* Tenure information (joining date, Last Date)
* Historical data regarding the performance of the employee (Quarterly rating, Monthly business acquired, designation, salary)

## Acknowledgements:
https://datahack.analyticsvidhya.com/contest/job-a-thon-november-2021/

## Data Dictionary:
### Train Data
MMMM-YY - Reporting Date (Monthly)

Emp_ID - Unique id for employees

Age - Age of the employee

Gender - Gender of the employee

City - City Code of the employee

Education_Level - Education level : Bachelor, Master or College

Salary - Salary of the employee

Dateofjoining - Joining date for the employee

LastWorkingDate - Last date of working for the employee

Joining Designation - Designation of the employee at the time of joining

Designation - Designation of the employee at the time of reporting

TotalBusinessValue - The total business value acquired by the employee in a month (negative business indicates cancellation/refund of sold insurance policies)

Quarterly Rating - Quarterly rating of the employee: 1,2,3,4 (higher is better)

### Test Data
Emp_ID - Unique Id for the employees

## Evaluation Metric:
The evaluation metric for this competition is macro f1_score.
