## Ensemble of ARIMA and LSTM model for Wiki pages
This notebook trains an ensemble of ARIMA (Autoregressive integrated moving average) model and LSTM (Long Short Term Memory) to predict Web Traffic on Wiki Pages.

### Problem

This is based on a time series problem on kaggle. We need to predict the traffic on Wiki Pages on certain dates.


### Data
The data provided here is available on kaggle.com https://www.kaggle.com/c/web-traffic-time-series-forecasting/data

### Models

We use statsmodels ARIMA model and keras LSTM RNN model to train our ensemble.

### Link to the kernel

You can directly have a look at the kernel at https://www.kaggle.com/screech/ensemble-of-arima-and-lstm-model-for-wiki-pages

### Screenshots with explanation

This is the form of data we will be getting. We convert it from csv to a pandas DataFrame.

![Input](./Screenshots/input_data.png?raw=true "Input")

Now we will visualize the data in form of a graph. These are the different pages on Wiki.

![Visualization](./Screenshots/DataViz.png?raw=true "visualize")

Now we train our ARIMA and LSTM models on this data and get the predictions.

#### For ARIMA model

![ARIMA](./Screenshots/SampleArima.png?raw=true "ARIMA")

In a similar way we train all ARIMA models. Rest of the graphs are available in the notebook.

#### For LSTM models

![LSTM](./Screenshots/sampleLSTM.png?raw=true "LSTM")

In a similar way we train all LSTM models. Rest of the graphs are available in the notebook.
