# Project Name
> Build a multiple linear regression model for the prediction of demand for shared bikes.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. We want to understand the factors affecting the demand for these shared bikes in the American market. We also want to:
* Know which variables are significant in predicting the demand for shared bikes.
* Know how well those variables describe the bike demands
* Build a multiple linear regression model to predict the demand on a given day.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Below are the conclusions after arriving at the final Model
- The final model has a `Adj. R-squared` value of `0.835`, `Prob (F-statistic)` value of `2.00e-189` and `r2_score`  value of `0.797` on the test set.
- From the coefficients of the model, we can say `temp` is the most impactful independent variable
- `windspeed`, `weathersit_2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist` and `weathersit_3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds` correspond negatively to the target variable as can be explained in eneral by the data dictionary provided

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas - Version 1.3.4
- matplotlib - Version 3.4.3
- Seaborn - Version 0.11.2
- statsmodel
- sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project mainly applies the concepts of Multiple Linear Regression.
- The data dictionary provided by the client was used for understanding the data.
- Resources on the web were consumed to understand various aspects of model building.


## Contact
Created by [@akintaliarkin] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->