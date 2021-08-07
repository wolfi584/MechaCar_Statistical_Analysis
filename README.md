# MechaCar Statistical Analysis Challenge

## Linear regression to predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- vehicle length and ground clearance

Is the slope of the linear model considered to be zero? Why or why not?
- The slope of the linear model is not considered to be zero, because there is a positive slope intercept number. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- Yes and no. The linear model does output data that can be considered for quality analysis. However, there are external factors in the testing environment that can have an impact on test results. For example, is the test conducted inside or outside? What was the weather on different days of the test? All of these variables should be considered because of their ability to impact results. 
![A](https://raw.githubusercontent.com/wolfi584/MechaCar_Statistical_Analysis/main/Resources/Challenge15_Part_1.PNG?raw=true)

## Summary statistics on suspension coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- Lots 1 and 2 have a variance that does not exceed 100 lbs per square inch. Lot 3 does exceed the 100 lbs per square inch. Since Lot 3 exceeds the requirement, all lots in total do not meet the required design specifications
![B](https://raw.githubusercontent.com/wolfi584/MechaCar_Statistical_Analysis/main/Resources/Challenge15_Part_2.PNG?raw=true)

## T-Tests on suspension coils
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.
- All of the t-tests I conducted had p-value results that were greater than .5. My interpretation of this is that the mean of the sample data is the same as or close to the mean of the entire population.
![C](https://raw.githubusercontent.com/wolfi584/MechaCar_Statistical_Analysis/main/Resources/Challenge15_Part_3.PNG?raw=true)


## Design study: Mechacar vs. competition
 - Tested metrics: MPG for city and highway driving, saftey rating, car price, and customer satisfaction rating. 
 - Alternative hypothesis: The Mechacar has more value than other cars in it's category because it has a higher fuel efficiency, better saftey rating, lower price, and a higher customer satisfaction rating than it's competitors.  
 - Statistical tests used to challenge alternative hypothesis: Summary statistics, one sided t-test, and p-value hypothesis tests
 - Data needed to run tests: fuel efficiency reports, consumer reports, Kelly blue book reports, and saftey rating reports.
