# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Build a multi linear regression model for bike sharing company BoomBikes
- The model identifies the factors responsible for determining the demand for shared bikes and build a model so that it can predict the future demand based on different conditions
- This should help BoomBikes dpredict the demand which will affect thier sale
- Dataset contains various factor like temperation,windspeed,humidity,weekends etc along with the user count.The model is depeloved using 70% of this data as training data set.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- A Linear regression model is built using various predictor variables to predict the demand for shared bikes

- The model predicts the dependent variabes as year,holiday,temperatur,humidity,Windspeed,Mist,Spring,Summer,Winter

- Following are the coeficients of different predictor variables

const 0.349279

yr 0.23146 1
holiday -0.0762 8 2 temp 0.533 8 97 hum -0.27 4 155 windspeed -0.2 3 0502 Mist -0. 0 22387 spring -0 . 059573 summer
0 .051385 winter

Negative coeficients denotes the demand decreases for increase in predictor variable.For example demand decreases on holidays or during Spring
- The model has been tested with the test data and found to have R squared similar to the train data set 0.095206



## Technologies Used
- python
- pandas
- seaborn(https://seaborn.pydata.org/)
- scikit-learn1(https://scikit-learn.org/stable/)
- statsmodel(https://www.statsmodels.org/stable/index.html)

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This Problem statement was designed by Upgrad (https://www.upgrad.com/)


## Contact
Created by [@debargha.ganguly@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
