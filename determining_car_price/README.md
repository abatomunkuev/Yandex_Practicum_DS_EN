# System to determine car value

[Jupyter Notebook viewer](https://nbviewer.jupyter.org/github/abatomunkuev/Yandex_Practicum_DS_EN/blob/main/determining_car_price/determining_car_price.ipynb)

This project shows: 
- ability of writing solid,structured Python code 
- ability of using existing utilities(libraries) for processing and analyzing data.
- ability of utilizing Machine Learning models:
    - CatBoost
    - XGBoost
    - LightGBM
- analytical and data pre-processing skills

Project involves:
1. Data preprocessing
2. Machine Learning model research:
    - Selection of model parameters
    - Choosing the best model to solve the problem



## Data
Provided data - historical data: technical specifications, packages and prices of cars.

|Column            |Description         |Column type | 
 |:---------------|:------------------------|:-------------|
 |DateCrawled     | the date the application was downloaded from the database|features      |
 |VehicleType     | vehicle type   |features      |
 |RegistrationYear       | registration year |features     |
 |Gearbox       | gearbox type |features     |
 |Power       | power (hp) |features     |
 |Model      | model |features     |
 |Kilometer      | mileage (km) |features     |
 |RegistrationMonth      | vehicle registration month|features     |
 |FuelType       | fuel type |features     |
 |Brand       | brand |features     |
 |NotRepaired       | whether the car has been repaired or not|features     |
 |DateCreated      | date of application form creation|features     |
 |NumberOfPictures | how many pictures of the car|features     |
 |PostalCode      | postal code of the application form owner (user)|features     |
 |LastSeen    | the date of the user's last activity|features     |
 |Price       | price (euro)    | target | 

## Task

A used car service is developing an app where you can find out the market value of your car. We need to build a Machine Learning model to quickly determine the value of the car.

## Task details
The company is concerned about:
- the quality of the prediction
- prediction speed
- learning time


## Libraries used
*pandas*
*numpy*
*sklearn*
*xgboost*
*catboost*
*lightgbm*
*matplotlib*
*seaborn*
*scipy*
