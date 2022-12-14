# Multiple Linear Regression- BoomBikes
> Build a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)



## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.  Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The      company is finding it very difficult to sustain in the current market scenario.
- dataset being used: day.csv



## Conclusions
- We have build our model based on following features:
  - temp (x2).
  - yr (x1).
  - windspeed (x3).
  - season_Spring (x4).
  - mnth_Jul (x5).
  - weathersit_Cloudy (x6).
  - weathersit_Thunderstorm (x7).
- Error terms are normally distributed.
- R2_Score for Training data set: ``0.82``
- R2_Score for Testing data set: ``0.80``-
- Final Equation $ y = 0.2349X_1 + 0.4126X_2 - 0.1591X_3 - 0.1462X_4 - 0.0837X_5 - 0.0774X_6 - 0.2696X_7 + 0.3001 $


## Technologies Used
- numpy 
- pandas 
- matplotlib.pyplot 
- seaborn
- sklearn
- statsmodels.api



## Acknowledgements

- References 
    - journal={Progress in Artificial Intelligence},
	- title={Event labeling combining ensemble detectors and background knowledge},
	- url={http://dx.doi.org/10.1007/s13748-013-0040-3},
	- publisher={Springer Berlin Heidelberg},
	- author={Fanaee-T, Hadi and Gama, Joao}.


## Contact
Created by [@impc043] - feel free to reach out!


