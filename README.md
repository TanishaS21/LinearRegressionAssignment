# Linear Regression Assignment

> This assignment is a programming assignment wherein we have to build a multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies And Libraries Used](#technologies-and-libraries-used)
- [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- Temperature has a high correlation with the demand of bikes. Every unit increase in temperature increases the demand by 0.549892
- Cloudy and light snow weather situation has a negative correlation with the demand in bike sharing.
- The demand of bike sharing is increasing over the years from 2018 to 2019.
- The equation of best fitted line based on model is
  cnt = 0.075009 + (yr _ 0.233139) + (workingday _ 0.056117) + (temp _ 0.549892) - (windspeed _ 0.155203) + (summer _ 0.088621) + (winter _ 0.130655) + (saturday _ 0.067500) + (september _ 0.097365) - (Cloudy _ 0.080022) - (LightSnow _ 0.287090)
- The adjusted R-squared of the model is 0.8253 and for test data set it is 0.7863
- Null Hypothesis is rejected as we have significant coefficient of the predictor variables.
- Assumptions of Multiple Linear Regression are satisfied.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies And Libraries Used

- python 3.9.12
- Jupyter Notebook 6.4.8
- Anaconda Navigator 2.2.0
- numpy 1.21.5
- pandas 1.4.2
- seaborn 1.4.2
- sklearn 1.0.2
- statsmodels.api 0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by Upgrad Linear Regression Assignment module.
- Practical Statistics for Data Scientists by O'Reilly
- Stack overflow
- Medium
- Stack Exchange
- Wikipedia

## Contact

Created by [@TanishaS21] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
