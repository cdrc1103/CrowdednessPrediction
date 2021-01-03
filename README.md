# DL_Project13e

## Crowdedness prediction in public transport under Covid-19
During Covid-19 pandemic social distancing in public transport is an important matter to prevent spreading the virus. Thus, it would be beneficial to know when and where there are bottlenecks in the public transport network. Our goal is to reduce the capacity problem by predicting the crowdedness for a specified time interval with RNNs. As a data basis, we mainly use check-in/check-out numbers of Rejsekort users. We supplement this information with data from counting sensors that are installed in a small fraction of buses.

|**Outline of the notebooks**||
|:---:|:---:|
|DataPreprocessing| Shows our initial analysis of the data and the transformation of the data into time series.|
|Approach_1_MultistepLSTM| Simple vanilla LSTM that is called repeatedly to generate a sequence of values instead of single outputs.|
|Approach_2_Seq2Seq| Contains the main results of our project. Encoder-Decoder architecture to generate an output sequence from a larger input sequence.|
|Rejsekort_and_Sensor_to_Total| Integrates additional data from video based passenger counting sensors.|
