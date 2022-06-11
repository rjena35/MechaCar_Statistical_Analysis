# MechaCar_Statistical_Analysis

## Purpose
The purpose of this analysis is to assist AutosRUs with their production troubles with the new MechaCar prototype. Here we are reviewing the production data for any insights to help the manufacturing team.

## Linear Regression to Predict MPG

According to the results of the model, we can see that vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the linear model. These variable have significant impact on the mpg.

The slope of the linear model is not considered zero because the given p-value is smaller than the significnace level 0.05.

This regression model does well with predicting the mpg. The model will predict mpg correctly 71% as indicated by the r-squared value.

![image](https://user-images.githubusercontent.com/98003050/173205165-56aa69aa-a5f8-410f-af22-827d270dad62.png)



![image](https://user-images.githubusercontent.com/98003050/173205178-eddce83b-02aa-433b-ace8-e494273116f0.png)



## Summary Statistics on Suspension Coils
According to the results, Lots 1 and 2 both are consistent with each other.The mean and median of the two lots are equal to each other. Lot 3 shoes a larger discrepancy. The variance is extremely higher than Lot 1 and Lot 2, and doesn't meet the deisign specifications. Altogether, when calculating the total data, design specs are met.

![image](https://user-images.githubusercontent.com/98003050/173206477-09a658c0-750b-443f-aa3c-3a0d80b87def.png)



## T-Tests on Suspension Coils
According to the results, Lot 1 and Lot 2 have higher p-values than Lot 3 (0.041). This low p-value raises concern, and this suggests that suspension coils for vehicles manufactured in Lot 3 should be closely monitored moving forward.


![image](https://user-images.githubusercontent.com/98003050/173207364-b64f6e51-eb22-4717-91b1-5cffa5d4972e.png)

![image](https://user-images.githubusercontent.com/98003050/173207375-7e786c38-c372-422e-be28-136658fe5ea6.png)

![image](https://user-images.githubusercontent.com/98003050/173207383-0f39f1ed-fa29-4c21-a3af-03674fdf8649.png)

![image](https://user-images.githubusercontent.com/98003050/173207387-87a2546a-3175-4fc7-8d0d-8aed753b6b3a.png)


## Study Design: MechaCar vs Competition
Any time a vehicle is purchased, one of the most commonly-asked quesitons is "How much horsepower does this have?", so this should be thenext study design. We can run a linear regression model to deteremine what variables play a role in determining a vehicle's horsepower. To get the regressin model, we will take the same data points from competition vehicles and MechaCar vehicles, and pit them against each other.
