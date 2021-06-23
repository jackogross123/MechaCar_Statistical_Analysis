# MechaCar Statistical Analysis

## Overview of the Analysis

AutosRUs’ newest prototype, the MechaCar, is suffering from production troubles. By running regression analyses and t-tests, I will review production data for AutoRU's newest prototype, the MechaCar, and provide insights that may help the manufacturing team. Additionally, I will design a statistical study to compare the vehicle performance of the MechaCar vehicles against vehicles from other manufacturers.

### Analysis Resources
* **Data Sources:** [MechaCar_mpg.csv](https://github.com/dwwatson1/MechaCar_Statistical_Analysis/blob/main/MechaCar_mpg.csv), [Suspension_Coil.csv](https://github.com/dwwatson1/MechaCar_Statistical_Analysis/blob/main/Suspension_Coil.csv)
* **Software:** R 4.1.0 for Windows, RStudio 1.2.5019 - Windows 10/8/7 (64 bit)
 
## Deliverable 1 - Linear Regression to Predict MPG

![Deliverable_One_LM.PNG](https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/deliverable1.png)

The linear regression model above estimates that: 

```mpg = (6.267)vehicle_length + (0.0012)vehicle_weight + (0.0688)spoiler_angle + (3.546)ground_clearance + (-3.411)AWD - 104.0```


## Deliverable 2 - Summary Statistics on Suspension Coils


<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png" width="600" >


<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png" width="600" >


## Deliverable 3 - T-Tests on Suspension Coils



<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/first_t_test.png" width="600" >


### Lot 1 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_1.png" width="600" >


### Lot 2 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_2.png" width="600" >


### Lot 3 T-Test

<img src="https://github.com/jackogross123/MechaCar_Statistical_Analysis/blob/main/Images/t_test_lot_3.png" width="600" >


## Deliverable 4 - Study Design: MechaCar vs Competition


**H0 (Null Hypothesis):** MechaCar's vehicle safety ratings are no different from its competitors 

**Ha (Alternative Hypothesis):** MechaCar's vehicle safety ratings are different from its competitors 

