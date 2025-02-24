# Bike Sharing Assignment
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contacts](#contacts)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
This project implements a linear regression model to analyze the factors influencing bike-sharing demand. It includes feature selection using Recursive Feature Elimination (RFE), model evaluation through R-squared scores, and checks for multicollinearity using Variance Inflation Factor (VIF). The analysis provides insights into the impact of categorical and numerical variables on the target variable, ensuring robust model performance and accurate predictions.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
>Key Features Impacting Demand: Season, year, and weather conditions significantly influence bike-sharing demand.

>Model Performance: The R-squared score of 0.733 indicates the model explains 73.3% of the variance in bike demand.

>Feature Selection Efficiency: Using RFE improved model interpretability by selecting the most relevant features.

>Multicollinearity Check: High VIF values for temp and atemp suggest strong correlation, which may affect model stability.

Final Linear Regression Equation:
cnt = 1283.75 + 49.84*temp + 57.28*atemp + -14.16*hum + -35.19*windspeed + 1312.94*season_2 + 1218.92*season_3 + 1855.35*season_4 + 1953.19*yr_1 + 124.19*mnth_2 + 446.13*mnth_3 + -35.86*mnth_4 + 238.42*mnth_5 + -12.79*mnth_6 + -371.50*mnth_7 + -103.24*mnth_8 + 604.04*mnth_9 + 299.39*mnth_10 + -438.83*mnth_11 + -332.79*mnth_12 + -301.92*holiday_1 + -53.08*weekday_1 + -120.67*weekday_2 + 29.09*weekday_3 + 52.85*weekday_4 + 109.68*weekday_5 + 390.76*weekday_6 + 319.78*workingday_1 + -483.91*weathersit_2 + -1874.02*weathersit_3


## Technologies Used
- Numpy - version 1.23.5
- Pandas - version 2.0.1
- matplotlib - version 3.7.1
- seaborn - version 0.12.2
- scikit-learn - version 1.6.1
- statsmodels - version 0.14.4


## Contact
Created by [@SarthakaMahapatra] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
