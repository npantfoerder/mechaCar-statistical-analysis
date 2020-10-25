# Statistics and R

## Overview of the Analysis
### Purpose


## Linear Regression to Predict MPG
*Write a short summary using a screenshot of the output from the linear regression, and address the following questions:* <br>
<kbd> <img src='https://github.com/npantfoerder/mechaCar-statistical-analysis/blob/master/Images/linear_regression.png' width=400> </kbd>
- Vehichle_length and ground_clearance were the two variables that provided a non-random amount of variance to the mpg values in the dataset.
- The slope of the linear model is not considered to be zero. This is because the p-value of the linear model was much smaller than the significance level, providing sufficient statistical evidence that the null hypothesis is not true.
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The r-squared value is 0.715, meaning that there is a 71.5% chance that future data points will fit this model. Therefore the linear model does predict mpg of MechaCar prototypes effectively. 

## Summary Statistics on Suspension Coils
*Write a short summary using screenshots from your total_summary and lot_summary dataframes, and address the following question:* 
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. The current manufacturing data meets this design specification for all manufacturing lots in total. Individually, lots 1 and 2 meet the specification, but lot 3 does not. Lots 1 and 2 had variances of 1.15 and 10.13. However, lot 3 has a variance of 220.01, which exceeds the 100 pounds per square inch specification.
<img src='https://github.com/npantfoerder/mechaCar-statistical-analysis/blob/master/Images/total_summary.png' width=375> 
<br>
<img src='https://github.com/npantfoerder/mechaCar-statistical-analysis/blob/master/Images/lot_summary.png' width=500>

## T-Tests on Suspension Coils
*Briefly summarize your interpretation and findings for the t-test results, include screenshots of the t-test* <br>
<kbd> <img src='https://github.com/npantfoerder/mechaCar-statistical-analysis/blob/master/Images/t_test.png' width=400> </kbd>

## Study Design: MechaCar vs Competition.
*Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. Think critically about what metrics would be of interest to a consumer: cost, city or highway fuel efficiency, horse power, maintenance cost, safety rating, etc. Address the following questions:*
- What metric or metrics are you going to test?
- What is the null hypothesis or alternative hypothesis?
- What statistical test would you use to test the hypothesis? And why?
- What data is needed to run the statistical test?

