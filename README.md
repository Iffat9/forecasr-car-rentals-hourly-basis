# forecasr-car-rentals-hourly-basis

Objective: To develop the machine learning approach to forecast the demand of car
rentals on an hourly basis.


Evaluation metric: The evaluation metric for this hackathon is RMSE score.


Public and Private Split:
Test data is further divided into Public (40%) and Private (60%) data.
Your initial responses will be checked and scored on the Public data. The final rankings
would be based on your private score which will be published once the competition is
over.


forcast_car_rental_hourly_basis .ipynb description:
Dependent variable: demand
Independent variable: date,hour
Created new variables ‘year, month, day, weekday’ in train and test data from the date
column.


Bivariate and Multivariate Analysis:
The demand for car rentals increases from 2018 to 2021 respectively.
November has the highest car rental demands followed by June and january.
In hourly basis the demand of the car increases during hour 7 to 15 and then respectively decreases
from the hour 15 to 22 , i.e the demand is high during working hour and least during 23(12 am) to 5
(5am) respectively
The demand for cars is highest on saturday and then on sunday, least on monday, tuesday and
wednesday.
For the first three days of the week the demand is less.
cars are rented mostly for Morning/Evening commutes on Weekdays, and mostly Daytime rides
on Weekends
