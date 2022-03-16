# Bike Sharing Assignment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is
finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its 
revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
		In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the 
nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from 
other service providers and make huge profits.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- BoomBikes facing dip in their revenue dur to Cororna, They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. 
- Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market
- We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
- Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Conclusions
- Temperature has a coefficient value of ‘0.5499’ indicated that a unit increase in "temp" variable, increases the bike demand by 0.5499 units.
- Weather of Light Snow has a coefficient value of '-0.2871' indicated that a unit increase in "Light Snow" variable, decreases the bike demand by -0.2871 units.
- Year has a coefficient value of ‘0.2331’ indicated that a unit increase in "yr" variable, increases the bike demand by 0.2331 units.
- From the summary of Model 11 (Final Model), we could see all the coefficient dont have value equals to zero which mean we can reject NULL hypothesis (H0 : B1=0, H1: B1 != 0)


## Technologies Used
- Pandas
- Scikit Learn
- Statsmodel
- Seaborn
