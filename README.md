# CaseStudy2DDS

Frito-Lay has given us the task to analyze their workforce trends to help retain employees and gain insight on salary predictions.

The dataset has 38 variables with 870 entries. The variables include age, gender, attrition, monthly salary, job role, department, number of years in company, stock option levels, marital status, and other descriptors of employees. 

The best variables that predicted attrition were Martial Status, Overtime Work, and Work-Life Balance. Cross-validating the attrition naive-bayes model resulted in a 0.75 sensitivity and a 0.65 specificity. The best variables that predicted monthly income was Job Level which the lm() model resulted in a low RMSE of $1476.

Analysis was done with Rstudio and R.
