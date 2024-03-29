# Stock Price Prediction using Time Series Modelling
The objective of this project was to predict stock prices using time series modelling. <br/> 
I used Kaggle Big Five Stocks data to predict APPL closing stock price. <br/> 
The data is available here: https://www.kaggle.com/datasets/abdullahmu/big-five-stocks <br/> 
I experimented with statistical and deep learning based time series models and compared their accuracies. <br/> 
The deep learning based time series model gave more accurate results.

## Auto Regressive Integrated Moving Average (ARIMA) Time Series Modelling
### Key Learnings
1. Learnt the concepts underlying ARIMA(p,d,q) models and the significance and estimation method of the values of p,d and q. <br/>
2. Interpreted the results of the model using accuracy measures, MSE and MAE <br/> 
3. Understood the limitations of ARIMA models: assumptions of linearity and Gaussian noise, challenges in dealing with outliers and long term memory

### Result
The best model turned out to be ARIMA(0,1,3): MSE: 0.016, MAE: 0.10

## Stacked Long Short Term (LSTM) Neural Network Time Series Modelling
### Key Learnings 
1. Learnt the architecture of stacked LSTM neural networks and the concepts underlying the different types of gates. <br/>
2. Interpreted the results of the model using accuracy measures MSE and MAE. <br/>

### Result
The stacked LSTM model trained for 100 epochs performed better than the ARIMA(0,1,3) model: MSE: 0.00047, MAE: 0.01
 
