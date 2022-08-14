# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG


The MechaCar dataset contains a sample size of 50 prototypes measuring the miles per gallon across multiple variables. The linear regression was calculated using R in RStudio.
Linear Regression
R script was applied to the dataset on several variables to get the following coefficients.

![MechaCar_mpg(2)](https://user-images.githubusercontent.com/103701561/184545746-807980aa-9b99-448d-8a75-515603b65389.png)


Summary of Linear Regression model
A summary of the linear regression can be displayed to determine the quality of the dataset. In this distribution of the residuals, the dataset fits in with the normal parameters, where the absolute value of the min and max are comparable |-19.47|~|18.58| and the median -.07 is close to zero.

![MechaCar_mpg(4)](https://user-images.githubusercontent.com/103701561/184545885-9b6f0b31-9d0b-47f6-80df-44493c3d9c8b.png)
![MechaCar_mpg(6)](https://user-images.githubusercontent.com/103701561/184545960-98969c26-331d-420a-a35d-4b35375f7e82.png)


1.	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
A 95% level of confidence was predetermined, meaning the p-value should be compared to alpha = .05 level of significance to verify if statistically significant.

Coefficients:
mpg: 0 < .05, statistically significant, non-random amount of variance
vehicle length: 0 < .05, statistically significant, non-random amount of variance
vehicle weight: .08 > .05 not statistically significant, random amount of variance
spoiler angle: .31 > .05 not statistically significant, random amount of variance
ground clearance: 0 > .05 statistically significant, non-random amount of variance
AWD: .19>=.05 not statistically significant, random amount of variance
In summary, vehicle length and ground clearance variables represent non-random amounts of variance as applied to the mpg values.


2.	Is the slope of the linear model considered to be zero? Why or why not?

Converting from scientific notation, all the slopes of the variables are shown to be non-zero even though some are close to zero:
Coefficients:
vehicle length: 6.267
vehicle weight: .001
spoiler angle: .069
ground clearance: 3.546
AWD: -3.411
The multiple linear regression formula for mpg = -.01 + 6.267(vehicle length) +.001(vehicle weight) +.069(spoiler angle)+3.546(ground clearance)-3.411(AWD), which results in a non-zero slope.


3.	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared is .7149, which is a strong correlation for the dataset and shows the dataset is an effective dataset. However, r-squared is not the only consideration for effectiveness. There may be other variables not included in the dataset contributing to the variation in the mpg.



 ## Summary Statistics on Suspension Coils
 
 ![Suspension_Coil(2)](https://user-images.githubusercontent.com/103701561/184546853-f31be523-e7c1-457d-ab81-ad30cc233e51.png)
 
![Suspension_Coil(4)](https://user-images.githubusercontent.com/103701561/184546859-d664a42d-28bc-47b6-8b79-4faa0bd4a37c.png)
