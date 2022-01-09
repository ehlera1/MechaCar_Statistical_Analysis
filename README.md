# MechaCar Statistical Analysis

## Overview

For this analysis, we've been working with Jeremey who only a few weeks ago was promoted to Lead Analyst at AutosRUs. Jeremy was approached by upper management about a special project. AutosRUs' newest prototype, the MechaCar is suffering from production troubles that are blocking the manufacturing team's progress. Using R and statistical analysis we will review the production data that might help provide insights for the manufacturing team. 

In this analysis we will: 
 - Use linear regression to predict MPG 
 - Show a statistical summary of the suspension coils
 - Preform a T-Test on the suspension coils
 - Design a study comparing the MechaCar to the competition
---
## Linear Regression to Predict MPG

 - The variables/coefficients that showed a non-random effect on the MPG of the MechaCar can be see in the below images and they were the vehicle length and ground clerance. 
 - The slope of the linear model cannot be considered zero. This is due to the fact that the P-value was much lower than the significance level. This means that the relationship between the variables and MPG is more than random chance.
 - This model does somewhat predict the MPG of the MechaCar prototype effectively as the r-squared value is 0.7149 which means it is approximately 71% accurate at showing effect on MPG. 

![DEL_1 1](https://user-images.githubusercontent.com/90698381/148694860-58204dac-a15a-4d65-a0e7-a5e64f59dc44.png)
![DEL_1 2 1](https://user-images.githubusercontent.com/90698381/148694861-e1a1a869-346a-40a3-ba5c-d302f303cc6b.png)
---
## Summary Statistics on Suspension Coils

The two below screen shots are the tables that we created to summaries the statistics in relation to the suspensions coils. 
Per the design specifications for the MechaCar suspension coils, it dictates that the variance of the suspension coils must not exceed 100 pounds per inch. Overall, the variance meets this criteria @ 62.29356. However, when reviewing the statistics by Lot it is clear to see that Lot 3 has a variance that is well outside the requirements as outlined in the design specifications. 

![DEL_2 1](https://user-images.githubusercontent.com/90698381/148694868-0df4f753-def8-40d0-bf66-7dd445209cc5.png)
![DEL_2 2 1](https://user-images.githubusercontent.com/90698381/148694871-28e1c7a7-3a3b-4ce2-8fa9-b2735a3b6d97.png)
---
## T-Tests on Suspension Coils

In our final analysis for this we reviewed the T-Tests on Suspension Coils. The below images are similar to the statics that we previous supplied for suspension coils in that we preformed the analysis for the entire manufacturing lot and we also broke the findings down be each unique lot. 
 - When reviewing the T-Test findings for all lots the it shows that they are not statistically different from the population mean, and the p= value is not low enough for us to reject the null hypothesis. 
 - Similar in findings to our summary statistics, when reviewing the T-Tests by lot, Lots 1 & 2 are not statistically different than the population mean but Lot 3 is. Based on these findings Lot 3 may need to be scrapped so they do not cause issues with the MechaCar suspension. 

![DEL_3 1 1](https://user-images.githubusercontent.com/90698381/148694884-c00361ab-2ac2-4022-a3dd-e0ba56470b4c.png)
![DEL_3 2 1](https://user-images.githubusercontent.com/90698381/148694889-fd60c9f1-6031-4e53-91c8-ca175b5e926a.png)

---
## Study Design: MechaCar vs Competition


Finally, after we have completed the needed analysis above addressing the production troubles occurring in manufacturing, we have thought about a future study to compare the MechaCar vs it's competition. With virtually all consumers having better access to information via the web and the ability to easily compare information on similar models we want to make sure that we can test metrics that show areas where MechaCar may have a competitive advantage vs it's competition as well as areas where it may fall short. 

### Metrics we are you going to test?
To star this analysis we are going to test the MPG of the MechaCar. With rising fuel costs and consumer concerns of global warming we feel that a vehicle's efficiency is one of the major determining factors considered in the purchase of a new vehicle.  

### Hypothesis
 - The Null Hypothesis is that most vehicles that are in the same class as MechaCar have very similar MPG numbers. 
 - The Alternative Hypothesis is that there are some car's in MechaCar's class that have superior MPG numbers. 
 - 
### Statistical Test of Hypothesis 
For testing our MPG hypothesis, we would use an ANOVA test for fuel efficiencies as well as incorporating a plot to visualize the data by make/model. 

### Data Need for Statistical Test
For this analysis we would need efficiency data from the individual make/model cars that would be in the same class as the MechaCare, ideally from a reputable source such as the EPA. 
