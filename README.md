# Project Name
> Predict the demand of bikes for a rental bike sharing company.


## Table of Contents
* Steps followed for prediction task.
* Observations
* Conclusions

<!-- You can include any other section that is pertinent to your problem -->

## Steps followed
- Reading and Understanding the data
- Visualising the data
- Splitting the data into training and testing sets.
- Rescaling of features
- Running Recursive Feature Elimination wto get 15 variables.
- Building model using statsmodel for detailed analysis
- Dropping features further on the basis of VIF and p value.
- Linear regression assumptions check
- Model Evaluation

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Observations
- 15 features taken from RFE
- Categorical variables seem to have more impact on dependent variable.
- In numeric variables temp features has more impact on target variable though its VIF was      pretty high initially

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Conslusion
Demand of bikes depends on these variables - yr , holiday, temp, windspeed, mnth_sep, weathersit_Light_snowrain, weathersit_Misty, spring, season_summer and season_winter.

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
