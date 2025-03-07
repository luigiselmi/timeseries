Time Series
===========
This repository is dedicated to time series forecasting. The notebooks contain examples in different domains, such as climate, air quality, finance, traffic, and models, from linear, stationary, non-stationary, seasonal models to deep learning models. Algorithms for time series forecasting used in the notebooks can be divided into two groups

1. Classic algorithms such as moving average (MA) and autoregressive moving average (ARMA)
2. Deep learning algorithms such as 1D CNN, LSTM, Transformers

Classic algorithms are based on polynomials that are fitted on the datasets to detect patterns such as trends, cycles, and random noise. The pros are simplicity and explainability, the cons is the short time window that can be learnt by these algorithms. Deep learning algorithms are better at finding more complex and longer patterns than linear trends and cycles. The cons of deep learning algorithms is the higher complexity to set up and train the models and lack of explainability.   

The links in the following list refer to notebooks in this repository or in other repositories that are related to time series. The notebooks are based on the following books and tutorials:

### Peixeiro - Time Series Forecasting in Python
The book showcases several classical time series algorithms such as MA, ARMA, ARIMA, SARIMA, and deep learning models such as LSTM, and frameworks based on [statsmodel](https://www.statsmodels.org/stable/index.html) and TensorFlow/Keras

* [Beijing Multi-Site Air Quality](beijing_multi-site_air_quality.ipynb)
* [Metro Interstate Traffic Volume Forecasting (Part 1)](traffic_forecast_part_1.ipynb)
* [Metro Interstate Traffic Volume Forecasting (Part 2)](traffic_forecast_part_2.ipynb)
* [Autoregressive LSTM](autoregressive_lstm.ipynb)
* [1D CNN for Time Series](cnn_timeseries.ipynb)
* [Feature engineering and time encoding](preprocessed_traffic_dataset.ipynb)
* [FAOSTAT Time Series](https://github.com/luigiselmi/climate/blob/main/iia/fao/faostat.ipynb)

### Chollet - Deep Learning with Python, 2nd Edition
This book contains 3 chapters dedicated to time series and natural language processing based on deep learning, LSTM, Transformers. The examples, based on TensorFlow/Keras, have been tested in the [dl_tensorflow](https://github.com/luigiselmi/dl_tensorflow) repository. 

### Glassner - Deep Learning - A Visual Approach
This book contains a chapter about Recurrent Neural Networks, and a chapter about transformers and the attention mechanism, with examples based on TensorFlow/Keras
* [Chapter 19: RNNs - Notebook 5: Sunspots](https://github.com/blueberrymusic/Deep-Learning-A-Visual-Approach/blob/main/Notebooks/Chapter19-RNNs/Chapter19-RNNs-5-Sunspots.ipynb)
* [Chapter 20: Attention and Transformers](https://github.com/blueberrymusic/Deep-Learning-A-Visual-Approach/tree/main/Notebooks/Chapter20-AttentionAndTransformers)

### Korstanje - Advanced Forecasting with Python
This is a book, similar to Peixeiro's, with chapeters dedicated to classical and deep learning algorithms for time series, with examples based on statsmodel and TensorFlow/Keras
* [Advanced Forecasting with Python - GitHub repository](https://github.com/Apress/advanced-forecasting-python/tree/main)

### TensorFlow Tutorials
* [Time Series Forecasting](https://www.tensorflow.org/tutorials/structured_data/time_series)

## Classic Textbooks
These textbooks describe the classical algorithms for time series.
* [Box, Jenkins, Reinsel, Ljung - Time Series Analysis - Forecasting and Control, 5th Edition](https://www.amazon.com/Time-Analysis-Forecasting-George-Box/dp/1118675029)
* [Brockwell, Davis - Introduction to Time Series and Forecasting, 3rd Edition](https://link.springer.com/book/10.1007/978-3-319-29854-2)
* [Montgomery, Jennings, Kulahci - Introduction to Time Series Analysis and Forecasting, 2nd Edition](https://www.amazon.com/Introduction-Analysis-Forecasting-Probability-Statistics/dp/1118745116)
* [Hyndman, Athanasopoulos - Forecasting: Principles and Practice, 3rd Edition](https://otexts.com/fpp3/) (Free online book with videos and examples based on R)

## Blog posts and articles
* [Karpathy - The Unreasonable Effectiveness of Recurrent Neural Networks](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)
* [Brownlee - Multivariate Time Series Forecasting with LSTMs in Keras](https://machinelearningmastery.com/multivariate-time-series-forecasting-lstms-keras/)