# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
<br/>The MechaCar_mpg.csv dataset contains mpg test results for 50 prototype MechaCars. The MechaCar prototypes were produced using multiple design specifications to identify ideal vehicle performance. Using R we will design a linear model that predicts the mpg of MechaCar prototypes using several variables/Coefficients.
## Linear Regression
<br/>Using the script to calculate the linear regression we get the below coefficients.
<br/><img width="752" alt="Screen Shot 2021-06-01 at 12 15 55 AM" src="https://user-images.githubusercontent.com/77771292/120266524-1cc91d00-c270-11eb-9681-e1b678babba8.png">

 ## Summary of linear regression
<br/> Using the script to calculate the summary of linear regression model we can determine the p-value and the r-squared value.
<br/><img width="752" alt="Screen Shot 2021-06-01 at 12 16 17 AM" src="https://user-images.githubusercontent.com/77771292/120266578-39fdeb80-c270-11eb-8ff3-0e98d9f80ab4.png">

## Predictions for linear regression
<br/>1. There are no variables that provide a non-random amount of variance to the mpg values in the dataset because the pr(>|t|) value is greater than 0.05. Which means that it has no significant impact on the mpg values and we can reject the null hypothesis.
<br/>2. The slope of the linear model is not considered to be zero because all the variables/coefficients are directly proportional to the mpg vales.
<br/>3. The linear model does not predict mpg of MechaCar prototypes effectively because the p value of the multiple linear regression is 5.35e-11 which is higher than 0.05 and is not signficant.

## Summary Statistics on Suspension Coils
<br/>The MechaCar Suspension_Coil.csv dataset contains the results from multiple production lots. In this dataset, the weight capacities of multiple suspension coils were tested to determine if the manufacturing process is consistent across production lots.

## The suspension coil’s PSI continuous variable across all manufacturing lots
<br/><img width="430" alt="Screen Shot 2021-06-01 at 12 17 23 AM" src="https://user-images.githubusercontent.com/77771292/120266816-b1337f80-c270-11eb-863c-422506b574b1.png">
<br/>The total_summary in the above table shows the mean, median, variance and SD for the PSI for suspension coil across all manugacturing units, and the variance of the suspension coil is under 100 PSI.

## The following PSI metrics for each lot: mean, median, variance, and standard deviation.
<br/><img width="541" alt="Screen Shot 2021-06-01 at 12 16 40 AM" src="https://user-images.githubusercontent.com/77771292/120266890-d32d0200-c270-11eb-9361-651557ad29bf.png">
<br/>The lot_summary in the above table shows the mean,median, variance and SD for the PSI for suspension coil across all manufacturing units individually. Looking at the table we can see the variance of Lot3 is higher than 100 PSI which is not acceptable.

## T-Tests on Suspension Coils
<br/>We will perform t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.
## To Determine if the PSI across all manufacturing lots is statistically different from the population mean of 1,500 pounds per square inch.
<br/>The p value is 1 which is greater than 0.05 and is therfore not significant and the null hypothesis can be accepted
<br/><img width="640" alt="Screen Shot 2021-06-01 at 12 37 56 AM" src="https://user-images.githubusercontent.com/77771292/120267293-ac230000-c271-11eb-935e-56d34153099d.png">
## To Determine if the PSI for each manufacturing lot is statistically different from the population mean of 1,500 pounds per square inch.
<br/>The p value is 1.568e-11 which is greater than 0.05 and is therfore not significant and the null hypothesis can be accepted.
<br/>Lot 1
<br/><img width="662" alt="Screen Shot 2021-06-01 at 12 19 13 AM" src="https://user-images.githubusercontent.com/77771292/120267028-1f784200-c271-11eb-83e3-3352c8483a3e.png">
<br/>Lot 2
<br/>The p value is 0.0005911 which is less than 0.05 and is therfore significant so the null hypothesis can be rejected.
<img width="625" alt="Screen Shot 2021-06-01 at 12 19 25 AM" src="https://user-images.githubusercontent.com/77771292/120267170-6e25dc00-c271-11eb-85ef-5825fcb186ba.png">
<br/>lot 3
<br/>The p value is 0.1589 which is greater than 0.05 and is therfore not significant so the null hypothesis can be accepted
<br/><img width="636" alt="Screen Shot 2021-06-01 at 12 19 35 AM" src="https://user-images.githubusercontent.com/77771292/120267207-7e3dbb80-c271-11eb-8d9e-f7592b2e7075.png">

## MechaCar vs Competition
<br/>The various comparable factors that MechaCar can perform against the competition would be cost,highway fuel efficiency, horse power, maintenance cost,seating capacity,PSI, mpg,ground clearence,fuel type,safety rating etc.

<br/>1. We can test the highway fuel efficiency,horse power and cost.Since these metrics are directly proportional we can justify the cost of vehicle comparing to the competition.

<br/>2. The null hypothesis is a statement of no difference between a sample mean or proportion and a population mean or proportion. The alternative hypothesis is a contradictory to the null hypothesis.The mean of metricA from the MechaCar can be equal or different than the mean of metricA from the competition.Using the t test we can calculate the p value and depending on this p value we can reject our null hypothesis if p value is smaller than 0.05 and support the alternative hypothesis or accept the null hypothesis and reject the alternative hypothesis.

<br/>3. Since we are comparing the means from two populations we can use two sample t test. Further as we want to know whether one population mean is greater than or less than the other, we can perform a one-tailed t-test.

<br/>4. The following data is needed to run the statistical test

	a. The mean of both samples
	b. The standard deviation of both samples
	c. The number of observations











