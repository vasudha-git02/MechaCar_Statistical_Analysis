# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
The strongest contributor of non-random variance seems to be the vehicle length with a p-value of 2.60e-12. The other strong contributor of non-random variance is the ground clearance with a p-value of 5.21e-8.

The slope of the linear model is not zero. We can see that the slope coefficients contain significant non-zero values (vehicle length, ground clearance, and AWD), and the p-values are less than the significance level of p=0.05.

Our r^2 value is 0.7149, which means the model does have good predictive power for the mpg.


<img width="650" alt="Del1_Output" src="https://user-images.githubusercontent.com/104597335/184863043-39d9a8f3-53e1-4d97-aac9-dc230de79fff.png">

## Summary Statistics on Suspension Coils

n the total summary, we can see the variance of all three lots in tandem does fall under the maximum variance of 100 PSI with a variance of 62 PSI.

In the lot summary, we see that the major contributor to the variance is lot 3 with a variance of 170 PSI with the other two lots having variances below 8 PSI.

In total, the manufacturing data meets the maximum variance in PSI requirement, but we can see that there are clearly big problems in lot 3 with a variance of 170 PSI. Lot 3 does not meet the maximum variance requirement.

- Total Summary

<img width="463" alt="Total_summary" src="https://user-images.githubusercontent.com/104597335/184864173-fcadcaaf-8442-4c2a-963f-f9b4eb7466b2.png">

- Lot Summary

<img width="463" alt="Lot_Summary" src="https://user-images.githubusercontent.com/104597335/184864201-9b3ef0c3-6014-4c6e-8c19-7aaab49b44d0.png">


## T-Tests on Suspension Coils

From our first t-test, we can see the sample mean is not statistically different from the population mean of 1500 PSI with a p-value of 0.06.

However, when we perform t-tests on the individual lots, we can see that although lots 1 and 2 are not statistically different from the population mean with p-values of 1 and 0.6 respectively, lot 3 does have a mean which is statistically different from the population mean with a p-value of 0.04.


<img width="650" alt="Del3_output" src="https://user-images.githubusercontent.com/104597335/184864811-3a1cb5b0-816e-4068-9ae8-d36c4a2ac129.png">
