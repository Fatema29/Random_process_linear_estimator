# Linear Estimator

In this project I have developed a general linear estimator to see if I can predict the size of a wild forest fire based on the environmental conditions such as the temperature and humidity.

I have downloaded the Forest Fires dataset from this link: https://archive.ics.uci.edu/ml/datasets/Forest+Fires

This dataset has 13 features – and I have used 7 of these to predict the last feature which is the area of the fire.

Specifically, I have used the following seven features which are:

a. FFMC: Fine-fuel moisture code, X1

b. DMC: Duff moisture code, X2

c. DC: Drought code, X3

d. ISI: Initial spread index, X4

e. temp: temperature, X5

f. RH: humidity, X6

g. Wind: wind speed, X7

Then I predicted the “area” (Y) – the last feature in the dataset which tells  how much of the area in the forest burned down under the conditions described by the seven features I have identified above.

The dataset has 517 observations. I have used the first 400 observations to train the model and the last 117 to test the model.

I have tried three combinations of different features.

Then I plot the graph of MSE for those 3 combinations.
