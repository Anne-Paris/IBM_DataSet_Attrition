# IBM_DataSet_Attrition
Analyzing and predicting attrition with IBM's employees' attrition dataset. 



The objective of this project was to analyze employee attrition, which is known to be a costly issue for organizations as it involves hiring and training new employees, often at a cost of 3 or 4 times the position's salary. With this in mind, we set out to answer the question “What makes an employee likely to quit their job?”. To answer this question and build a model that would potentially be helpful to an HR professional, we found a hypothetical dataset created by IBM data scientists on Kaggle specifically targeting employee attrition. 


	The variables within our dataset can be classified into four categories. The first category is Job Related, which includes an employee’s job role, department, job level, and travel frequency. The second category is Demographics, which comprises an employee’s age, gender, relationship status, educational background, and the distance between an employee's home and office. The third category includes career-related variables, such as the number of companies an employee has previously worked for, years with the current company, years in their current role, and years since their last promotion. Finally, the last category pertains to pay, which includes daily rate, hourly rate, monthly income, and monthly rate.


Our findings suggest that the majority of employees who left had job levels of 1 and 2 (reserved for entry-level or recently hired employees). Additionally, age was a significant factor in all our models, with our dataset showing that people younger in age are more likely to leave their jobs. Interestingly, 96% of sales representatives with a job level of 1 are at high risk of leaving, which is why so many of our models wrongly predicted that sales executives (higher level, fewer employees) would quit. Moreover, sales representatives and laboratory technicians account for 46.33% of employees who quit, making them the primary areas of concern for businesses seeking to retain employees.
