# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

###### Summary

Vehicle length ( p = 2.60e-12) and ground clearance (p = 5.21e-08) provided a non-random amount of variance to the mpg values in the dataset. The slope is not considered to be zero. The slope (r-squared) was .6825. The linear model can predict mpg effectively because p value is less than .05 and the multiple r-squared is .6825 which makes the prediction ~68% effective.

![alt text](https://github.com/CCoelho372/MechaCar_Statistical_Analysis/blob/main/linear_regression.PNG)


## Summary Statistics on Suspension Coils

###### Summary

The current manufacturing data meets the design specifications for all manufacturing lots in total but not each lot individually. The toal PSI variance is 62.3 which is under 100. There are some lots such as Lot 3 which has a PSI variance of 170. 

![alt text](https://github.com/CCoelho372/MechaCar_Statistical_Analysis/blob/main/total_summary.PNG)

![alt text](https://github.com/CCoelho372/MechaCar_Statistical_Analysis/blob/main/lot_summary.PNG)

## T-Tests on Suspension Coils

###### Summary

Lot 1 is not statistically different from the population mean of 1,500 pounds per square inch. For lot 1, t=0, and it has a p-value of 1. Only random chance in lot 1 would cause a difference from 1,500 pounds. Lot 2 has a p-value of .6072 which would give a high chance of being 1,500 pounds of psi. Lot 3 has a p-value of .04168 which means the chance of the PSI being 1,500 pounds are not as statistically significant. I would use tires from lot 1 and 2 for more reliability.

![alt text](https://github.com/CCoelho372/MechaCar_Statistical_Analysis/blob/main/t.test_psi.PNG)

## Study Design: MechaCar vs Competition

###### Study Design

The metrics that will be tested in this study design are MechaCar cost in relation to the competition based on safety rating. We will determine cars with high safety ratings have a higher cost. Otherwise cars cost does not increase with a higher safety rating. A linear regression model will be developed for MechaCar and the competition. An r squared close to 1 will be the result for the alternative hypothesis to be true. Most important data for the statisitcal statistics will be car make, cost, car size, and overall safety rating.



