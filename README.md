# BeijingAirPollutionPrediction
 MultivariableLSTM
It is a deep learning model with one layer LSTM to predict the PM 2.5 from 'dew', 'temp', 'press', 'wind_direction', 'wind_speed', 'snow' and 'rain' historical data in 5 years.

I added some data engineering functions to the data frame like sliding windows, muti-step jumpers to get the periodicity in the data. Yes, like the NeuralProphet.But this is for muti-variables~
