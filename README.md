# Project Name
> Bike Rental Case Study.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- To build a multiple linear regression model for the prediction of demand for shared bikes.
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free
- The goal is to identify key variables that serve as strong acceleration in its revenue by identifying which variables are significant in predicting the demand for shared bikes and How well those variables describe the bike demands
- The Data Set, Provided by UpGrade It includes the complete Bike Sharing dataset and data dictionary, which provides detailed descriptions of the variables included in the dataset

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- In this analysis, the following categorical variables are considered:
  1.	Season: Spring, Summer, Fall, and Winter
  2.	Weather Situation (Weathersit): Clear, Mist, Light Snow, and Heavy Rain
  The target variable, cnt, represents the total count of rental bikes (including both casual and registered users). The effects of these categorical variables on the target variable, cnt, are summarized as follows:
- Season (Categorical Variable):
	The highest average cnt is observed in the Fall season, followed by Summer and Winter.
	The lowest average cnt occurs in Spring.
- Weathersit (Categorical Variable): 
	The highest average cnt is observed during Clear weather, followed by Mist.
	The lowest average cnt is recorded during Light Snow.
	No rentals (i.e., cnt = 0) are observed during Heavy Rain
- Top 3 factors are  1. temp 2. weathersit (Weather Situation) 3. Season
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Programming & Libraries: Python, NumPy , Pandas, Matplotlib, Seaborn, sklearn, statsmodels  
- Analytical Technique : Exploratory Data Analysis (EDA) , Data Preparation, Multilinear Regression,  Residual Analysis of the train data, Making Predictions Using the Final Model, Model Evaluation

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was part of upGrade IIITB Machine Learning & AI course


## Contact
Created by [@sushantdubey007] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->