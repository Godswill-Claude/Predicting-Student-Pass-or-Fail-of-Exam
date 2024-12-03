# Predicting-Student-Pass-or-Fail-of-Exam

Logistic regression is one of the supervised ML model algorithms. It is ideally suited for business analytics 
applications where the target variable is a binary decision (fail/pass, response/no response, etc.). Unlike linear
regression, it works well with data that is not linear.

This project uses logistic regression model building to predict Predict whether a student will pass or fail an exam based
on the number of hours they study. An output (prediction) of 1 means Pass, while 0 means Fail. This is a supervised classification problem.

## Dataset
For this project, the following code was used to create a synthetic dataset made up of 2 variables - 'Hours_Studied' (predictor variable) and 'Pass' (target variable).

data = {
    'Hours_Studied': [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20],
    'Pass': [0, 0, 0, 1, 1, 1, 0, 0, 0, 1, 1, 0, 1, 0, 1, 1, 1, 1, 0, 0]
}
df = pd.DataFrame(data)
    
## Tools/Applications/Softwares/Packages Used for the Project
The python programming language, along with libraries such as Sci-kit learn, pandas, numpy, Seaborn and matplotlib, was used for the explorations and visualizations contained in this work.

## Key Insights for Analysis/Investigation
In this project, I endeavoured to find out the effect of a single predictor variable, Hours_Studied, on the Pass/Fail tendency of a student.

## Summary of Findings
It was discovered that the Hours_Studied does not have a linear relationship with the Pass/Fail outcome.
The logistic regression model prediction would do better with more training data, and the prediction of Pass/Fail would depend on other factorsin addition to Hours_Studied, such as number of classes attended by student, etc.
