# MechaCar Statistical Analysis

## Overview of the Analysis

AutosRUs’the MechaCar, the newest prototype, is suffering from production troubles that are blocking the manufacturing team's progress. By running regression analyses and t-tests, I will review production data for  the MechaCar and provide insights that may help the manufacturing team. Additionally, I will design a statistical study to study the MechCar against other top manufactured cars.

### Analysis Resources
* **Data Sources:** [MechaCar_mpg.csv](https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/MechaCar_mpg.csv)
* **Software:** R, RStudio
 
## Deliverable 1 - Linear regression to predict Miles per Gallon

![Deliverable_One_LM.PNG](https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/deliverable1.png)

Our linear regression model uses the inputs:

mpg = (6.267)vehicle_length + (0.0012)vehicle_weight + (0.0688)spoiler_angle + (3.546)ground_clearance + (-3.411)AWD - 104.0

- The vechicle lengths, weights, angle, and ground clearance are likely to produce an MPG that is not random.
- A 70% r squared tells us that only 30% of the regression can not be explained by the model
- The p value tells us that there is statistical significance from our findings.


## Deliverable 2 - Summary Statistics on Suspension Coils

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png" width="600" >

Lot 3 has high amount of variance which means that the data is very spread out.

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png" width="600" >


## Deliverable 3 - T-Tests on suspension coils


<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/first_t_test.png" width="600" >
The means accorss all of the lots are very similar.



### Lot 1 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_1.png" width="600" >
The p-value here is 1 which means we can disregard the t-test.

### Lot 2 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_2.png" width="600" >

The p-value here is 0.61 which means we cannot fail or reject this hypothessi.

### Lot 3 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_3.png" width="600" >

The p-value here is very small which means we can fall or reject this hypothesis.

## Deliverable 4 - Study Design: MechaCar vs Competition

Testing the safety of the MechaCar vs its competition.

**H0 (Null Hypothesis):** MechaCar's vehicle safety ratings are the same as its competitions

**Ha (Alternative Hypothesis):** MechaCar's vehicle safety ratings are not the same as its competitors.

