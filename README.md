# Employee performance dashboard

### Problem statement
INX Future Inc , (referred as INX ) , is one of the leading data analytics and automation solutions provider with over 15 years of global business presence. INX is consistently rated as top 20 best employers past 5 years. INX human resource policies are considered as employee friendly and widely perceived as best practices in the industry.

Recent years, the employee performance indexes are not healthy and this is becoming a growing concerns among the top management. There has been increased escalations on service delivery and client satisfaction levels came down by 8 percentage points.

CEO, Mr. Brain, knows the issues but concerned to take any actions in penalizing non-performing employees as this would affect the employee morale of all the employees in general and may further reduce the performance. Also, the market perception best employer and thereby attracting best talents to join the company.

Mr. Brain decided to initiate a data science project , which analyses the current employee data and find the core underlying causes of this performance issues. Mr. Brain, being a data scientist himself, expects the findings of this project will help him to take right course of actions. He also expects a clear indicators of non performing employees, so that any penalization of non-performing employee, if required, may not significantly affect other employee morals.

### Tech stack
Power bi - For creating visualizations.

### Key finding
1. There are a total of 1200 employees in the dataset. None are classified as low performing. The distribution is 158 Good, 750 Excellent, and 114 Outstanding employees. Across departments, Excellent performers are more than Good or Outstanding.
2. Attrition count is 178 (employees who left). Top three departments with highest attrition are: Sales (18.77%), Development (14.13%), and Research & Development (12.83%). Notably, many Excellent performers are among those who left.
3. For employees who left: 
  - Outstanding employees who left showed low job satisfaction (44%), low environment satisfaction (33%), and 22% low employee relationship satisfaction. None reported poor work-life balance.
  - Good employees who left showed 58% low and 36% medium environment satisfaction, 25% low job satisfaction, 32% low/medium job involvement, and 13.9% poor work-life balance.
  - Excellent employees who left showed 30% low job satisfaction, 23% low relationship satisfaction, 10% low job involvement, and 9.6% low work-life balance.
4. Among currently working employees: 32% report low job satisfaction, 17.5% low relationship satisfaction, 16.9% low environment satisfaction, 4.7% low job involvement, and 4.6% poor work-life balance.
5. Outstanding employees have high job satisfaction overall (39.4% very high, 25.4% high), but 23% still report low satisfaction and 37.4% report low relationship satisfaction. They show no poor work-life balance and receive the highest promotions and salary hikes.
6. Excellent employees (the largest group) show over 50% high or very high job satisfaction, but 17.6% have low satisfaction, 16% low relationship satisfaction, 12.9% low environment satisfaction, and 4.9% poor work-life balance. Compared to Outstanding employees, they receive fewer promotions though their hourly rate is nearly the same.
7. Good employees (average performers) show 18% low job satisfaction, 38% low/medium environment satisfaction, and 7% poor work-life balance. They receive fewer promotions than Excellent/Outstanding employees and tend to spend more years under the same manager. Their average hourly rate is more than excellant employees.
8.	Analysis of training times reveals that Excellent performers have the highest average training time (2.8 hours), followed by Good performers (2.76 hours), with Outstanding performers having the lowest average (2.71 hours). 

### Conclusions
- Low and medium job satisfaction is a recurring issue across all performance levels.
- Environment satisfaction and employee relationship satisfaction strongly influence attrition.
- A significant portion of high-performing employees (Excellent and Outstanding) left due to low satisfaction, indicating retention issues.
- Promotions and career progression opportunities appear limited for Good and Excellent employees compared to Outstanding employees, possibly affecting motivation.
- Work-life balance is generally not a major issue, but still affects a small percentage of employees.
- The hourly rate does not directly correlate with employee performance, suggesting potential issues with salary compression where good-performing employees are paid more than more productive employees.

  Dashboard png: ![Dashboard Preview]([https://github.com/savio999/employee_performance_dashboard_analysis/blob/main/dash.png])
  Dashboard link: https://app.powerbi.com/view?r=eyJrIjoiYWRhNzVkY2YtOTc0OS00ZWFlLTlmNGMtZTcyMTFiNzA5YmU0IiwidCI6Ijc1Y2VlNjM4LWJjNjItNDFhYi05M2ZjLTk2MzU5M2VkMjc1MCJ9


