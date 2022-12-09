# Green-Energy-Demand-Forecast
### Analytics Vidhya -JOB-A-THON - November 2022

### Problem Statement:
To predict the Green Energy demand for coming future based on 12 years data on hourly basis.

#### Evaluation Metric: RMSE

#### Approach:
•	Converting data-type to date -time format
•	Splitting of Date-time input into day, month, year and time.
•	Replacing null values using grouping and aggregating functions.
•	Preprocessing of Data: Standard Scaling, Min-Max Scaling and Robust Scaling applied.
•	Feature Selection 
•	Model Fitting
#### Algorithms	(R2, RMSE)

Random Forest Regressor	(0.5822 , 47.7477)

Hyperparameter tuning and Cross Validation with RF	(0.5822, 47.7477)

XGBRegressor	(0.4658, 53.9924)

LGBMRegressor	( 0.5821 ,47.7530)

CatBoostRegressor	(0.5822 , 47.7482)

RF with Feature Engg.	(0.5822002701964284	, 9.400658560987301)

•	The energy was predicted with model depicting RMSE 9.40065.

### Source: JOB-A-THON - November 2022 (analyticsvidhya.com)
### AV Rank: 437 / 6388



