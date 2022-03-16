# Bike Sharing System 
> Using Linear regression model, predict different feature and variables which impact the demand of bike sharing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- What is the background of your project?</br>
  BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.
  The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.  
- What is the business problem that your project is trying to solve?</br>
 To maximize the revenue and analyze different factors that impact the demand of boombikes
- What is the dataset that is being used?</br>
 We are analyzing the data set of two years 2018 and 2019 from boombikes.


## Conclusions
<b>Final equation:</b></br>
 cnt = 0.171244 + (0.228581 x yr) + (0.052441 x workingday) + (0.595988 x temp) - (0.170916 x hum) - (0.188772 x windspeed) + (0.082670 x summer) + (0.135504 x winter) + (0.062458 x sat) - (0.239137 x Light Snow) - (0.053623 x Mist) - (0.043937 x July) + (0.092832 x September)</br>
 <b>Conclusion:</b>
- Booking of bike demand increased in 2019 as compare to 2018
- With increase in temperature demand of bike booking increases 
- Humiditiy,windspeed,Light Snow,Mist and  mnth july has negatively impact the demand on bik, with increase in hum demand decreases
- Increase in demand i=of bike booking on working day as compare to non-working day
- Summer and Winter has more bike booking demand and is positively correlated.


## Technologies Used
- Python - Python 3.10.2</br>
- numpy - 1.21.5</br>
- seaborn - 0.11.2
- matplotlib - 3.4.3
- Pandas - 1.3.4</br>
- sklearn - 0.24.2</br>
- statsmodels - 0.12.2


## Acknowledgements
- This research was supported by Educational organisation Upgrad and under the guidance of our mentor  
 who helped us learn and work towards the assignment.


## Contact
Created by [aajjiitt] - https://github.com/aajjiitt/- feel free to contact me!
