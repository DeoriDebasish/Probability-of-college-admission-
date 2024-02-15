# Probability-of-college-admission-
## Business Problem
Jamboree has helped thousands of students like you make it to top colleges abroad. Be it GMAT, GRE or SAT, their unique problem-solving methods ensure maximum scores with minimum effort.
They recently launched a feature where students/learners can come to their website and check their probability of getting into the IVY league college. This feature estimates the chances of graduate admission from an Indian perspective.

Help Jamboree in understanding what factors are important in graduate admissions and how these factors are interrelated among themselves. It will also help predict one's chances of admission given the rest of the variables.

## Approach
- Checked for missing values and outliers
- Performed univariate,bivariate and multivariate analysis
- Used linear regression in finding the weights or coefficients of each feature for predicting the chance of admission in a college.
- Used linear regression for predicting the chance of admission in college and also tested for the assumptions of linear regression.
- Performed hyperparameter tuning for regularization methods and also checked how the model performs with Ridge, Lasso and Elastic Net regression.

## Business Insights
- With the increases in CGPA,GRE and TOEFL scores the chance of Admit also increases.
- It is observed that students with a research experience have a greater median chance of admit than students with no research background.
- Students with research background have a good chance of getting admitted with high SOP, LOR strengths and University ratings. 

## Recommendations
- Because of the strong correlation between GRE, TOEFL and CGPA additional independent features are required to enhance the accuracy of the model.
- Students with research experience have better LOR,SOP scores and get admitted to universities with good ratings, so more awareness about research should be organized.
- Students should be advised to have a better CGPA as CGPA has a strong correlation with the chance of getting admitted.
