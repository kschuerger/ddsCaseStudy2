# ddsCaseStudy2 Executive Summary

The client, DDSAnalytics, is interested in leveraging data science for talent management, and has tasked my team with conducting an analysis of existing employee data, before green lighting the larger data science initiative. The following case study explores factors leading to attrition, using a data set provided by Frito Lay, in an effort to develop a model that will aid in predicting employee turnover.  

Using ROC analysis of Naive Bayes on an undersampling of the data, it was determined that the top 3 contributors to employee turnover are: Overtime, Monthly Income, and Total Years Worked. Using these variables only, it was possible to determine whether an employee would experience attrition with an overall accuracy of approximately 66%. 

We were also asked to identify the top variables contributing to employees' monthly income. Using different automatic variable selection techniques on a linear regression model, it was determined that the top variables are: Business Travel, Job Level, Job Role, Percent Salary Hike, Performance Rating, and Total Working Years. 
Using a linear model created with these variables, it is possible to predict the mean monthly income for an employee with an accuracy of plus or minus $991.07, and to account for approximately 95.4% of the variation in the means of monthly income.
