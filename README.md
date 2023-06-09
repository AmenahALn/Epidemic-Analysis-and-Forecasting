## Epidemic-Analysis-and-Forecasting
we conducted a comprehensive analysis of the epidemics. Our focus was on parameter estimation, forecasting the spread of the virus, and evaluating different models' performance. Here is a summary of our findings: 
#### 1. Parameter Estimation and Forecasting the Spread of Epidemic.
* To predict the short-term forecast of confirmed cases, we applied the logistic growth model.
* The logistic model yielded a root mean square error (RMSE) of 5229.7 and 1,924.4, indicating a good fit.
* We assessed the performance of our model by evaluating its goodness of fit.
<img src="https://github.com/AmenahALn/Epidemic-Analysis-and-Forecasting/blob/main/logistic.JPG" alt="Image" width="300" height="200">

#### 2. Gaussian Model and Reproduction Numbers.
* We employed the Gaussian model to fit the daily number of confirmed cases, considering reproduction numbers.
* The following Figure illustrates the Gaussian model's fit to the daily number of confirmed cases, showing a good alignment with the actual data.
<img src="https://github.com/AmenahALn/Epidemic-Analysis-and-Forecasting/blob/main/gus.JPG" alt="Image" width="300" height="200">

#### 3. Prediction of the Epidemic
* We projected the future spread, considering the significant increase in confirmed cases expected.
* The Gaussian model was employed to estimate the value and timing of the expected peak, using the logistic model to determine growth rates.
* The following Figure presents three different scenarios, illustrating the predicted number of cumulative cases and daily cases, with peak times.
<div style="display: flex;">
  <img src="https://github.com/AmenahALn/Epidemic-Analysis-and-Forecasting/blob/main/gus_senrio.JPG" alt="First Image" style="width: 50%;">
  <img src="https://github.com/AmenahALn/Epidemic-Analysis-and-Forecasting/blob/main/cum_senrio.JPG" alt="Second Image" style="width: 50%;">
</div>
