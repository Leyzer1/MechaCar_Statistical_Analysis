# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

Using the miles per gallong dataset we performed linear regresion to predict the mpg using vehicle lenght, weight, spoiler angle, clerence, and all wheel drive variables.

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Two variables have non-random varience: The ground clearence and the vehicle lenght. Both have a high significance because both have a small p-valu-es. 

- Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero because the independent variables had an effect in the dependent variables in the linear regression.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

To see if the linear model see is effective we look at the r-square value. The r-square is 0.7149 which indicates thatr out of 100 insatnces, the model can predict the mpg of the MechCar about 71 times. With this result we can say the model is effective.

**Results:**
![mpg_linear_regression](https://user-images.githubusercontent.com/95899763/163599190-c19f6126-33cf-486e-b91b-e38ca244891e.PNG)

## Summary Statistics on Suspension Coils

Using the supsension coils dataset we created totals summary table to get the mean, median, varience, and standar deviation for 150 vehicles. We also created a lot summary table that devide the cars into lots. 

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

From the summary table we see that the varuience is 76.23 psi which does not meet the design specifications. We then look at the lots table and see that the first two lots do meet specifictions but the third lot does not meet it because the varience is very large.


**Results:**

![total_summary](https://user-images.githubusercontent.com/95899763/163602255-8d4c68d3-1086-4538-b86a-557d8a9b7e11.PNG)

![Lot_summary](https://user-images.githubusercontent.com/95899763/163602292-127b4fdf-97fa-4532-8791-77048cf8860f.PNG)


## T-Tests on Suspension Coils

- Are all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch?

We used the t-test to tested four groups: All three lots together, Lot 1 called pop1, Lot 2 called pop2, and Lot 3 called pop3. Taking account that significance level of 95% we found that all four p-values were greater than .05 which indicates that we fail to reject that there is a statistical difference between all four groups. 

**Results:**

![t-test](https://user-images.githubusercontent.com/95899763/163603905-f4b5db2a-ed12-4071-a499-ce1e93067206.PNG)

