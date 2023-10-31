# nyc_airbnb_capstone
## Overview
Airbnb is a marketing company that acts as a broker to provide short-term homestay experiences that offer several advantages like exposure to everyday life in another location, and the opportunity to experience local culture and traditions. Multiple reports forecast an increase in future Airbnb market capital and revenue with a growing economy.
## Goals
Our client is a successful investment and venture capital firm based in New York, owns several successful businesses and now wants to invest in new york based Airbnbs but wants to understand in-depth knowledge and information about the market before strategic decision-making.
## Data Specifications
This project will use [open-source data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) data of the year 2019 from AirBnb.

The dataset of 48,896 rows contains information about location, room type, prices, reviews, availability, and host information.

## New York Map
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/New_York_City_Map.png" width="800" height="600"></img>
## Neighbourhood
<img src = "https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Neighbourhood%20Plot.png">

## Continous Variable Relationship with Price
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Continous%20Variable%20Relationship%20with%20Price%20Plot.png" height="500"></img>

## Correlation Matrix
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Correlation%20Matrix.jpg"></img>
## Wordcloud
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Word%20Cloud.jpg"></img>
## Metrics
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Mean%20Absolute%20Error_MSE.jpg"></img>
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/Mean%20Square%20Error_MSE.jpg"></img>
<img src="https://github.com/ttariqaziz/nyc_airbnb_capstone/blob/main/Plots/R2_Score.jpg"></img>
## Model Comparison
| Model  | Mean Squared Error | R2 Score  | Mean Absolute Error |
| ------------- | ------------- | ------------- | ------------- |
| Linear Regression  | 0.22 | 40.58 | 0.17 |
| Decision Tree  | 0.21 | 48.2 | 0.15 |
| Bayesian Regression  | 0.22 | 40.58 | 0.17 |
| Ridge Regression  | 0.22 | 40.58 | 0.17 |
| Lasso Regression  | 0.22 | 40.58 | 0.17 |
| Gradient Boosting Regression  | 0.19 | 57.31 | 0.14 |

### We can see that the Gradient Boosting Regression model has the highest R2 score value and the least error. Hence it is the best model for our Airbnb project.

