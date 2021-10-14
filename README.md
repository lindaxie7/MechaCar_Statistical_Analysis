# MechaCar_Statistical_Analysis
AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles that are blocking the manufacturing team’s progress. We are going to review the production data for insights that may help the manufacturing team.

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. The two variables that had the most amount of random variance are ground_clearance and vehicle_length

- Is the slope of the linear model considered to be zero? Why or why not?

No, the slope of the linear model is not considered to be zero, because the p value is 5.35e-11, it is very small, there is a significant linear relationship between the independent variables and the dependent variable 

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes, based on the summary and the plot, we can conclude that there is a significant, linear relationship between the independent variables and the dependent variable, it is predict effectively. 
![1](https://user-images.githubusercontent.com/38533045/136679215-18ff4a17-9b35-49a5-87b3-64bea3c00839.png)

![3](https://user-images.githubusercontent.com/38533045/136679249-f5ba4c59-c4c4-488f-bb00-ff7432dc3f15.png), 

![2](https://user-images.githubusercontent.com/38533045/136679257-adf973f9-19c8-4604-9d2d-82a7e272d22a.png)

## Summary Statistics on Suspension Coils
- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
![Capture1](https://user-images.githubusercontent.com/38533045/137307289-8004a23b-ae64-4e29-9cf3-155a568f4c4f.JPG)

No, the current manufacturing data does not meet the specification that the suspension coils must not exceed 100 pounds per square inch, in the total_summary, we can see that the variance is 62.29356, which is less than 100 pounds per square inch. 
![Capture1](https://user-images.githubusercontent.com/38533045/137307289-8004a23b-ae64-4e29-9cf3-155a568f4c4f.JPG)


No, not all individually manufacturing lots meet this design specification, in the lot_summary, we can see that the variance for lot1 is 0.9795918, the variance for lot2 is 7.4693878, the variance for lot3 is 170.2861224, so only lot3 meet the specification that the suspension coils must not exceed 100 pounds per square inch.
