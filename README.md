# human_activity_recognition_transfer_learning

## Description
This project was done as a semester-long final project for 519 Applied ML course in 2022 Fall with Andrew Raine and Khanh Vy Nguyen.
We built a time-series machine learning model that predicts the human activity given a set-lenght time series features (gyrometer, accelerometer data).

## Datasets
The datasets we have used are
- [MHealth dataset](http://archive.ics.uci.edu/ml/datasets/mhealth+dataset) from UCI dataset
- [HAR dataset](http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions) from UCI dataset

## Models
We have used:
- 1D CNN models (for time series classification and transfer learning)
- RNN models (for time series classification and transfer learning)
- MLP layer that alignes the feature space of the Mhealth dataset and HAR dataset before moving onto transfer learning

## Results
The final report for this project can be accessed [here](https://docs.google.com/document/d/1i-oTHXMTh5OkLE-sfEzLcOz0YF4-GHUW/edit?usp=sharing&ouid=106243608498293248839&rtpof=true&sd=true)

## References:
- Banos et al., “mHealthDroid: a novel framework for agile development of mobile health applications”, IWAAL 2014.
- Faouzi, “Time Series Classification: A review of Algorithms and Implementations”,  HAL, 2022.
- Hochreiter et al., “Long Short-Term Memory”, Neural Computation 1977.
- Stisen et al., "Smart Devices are Different: Assessing and Mitigating Mobile Sensing Heterogeneities for Activity Recognition", SenSys 2015.
- Uddinet al., “Human activity recognition using wearable sensors, discriminant analysis, and long short-term memory-based neural structured learning”, Scientific Reports 2021.




##TODOs
-[ ] Train a better MLP model that aligns the feature space of MHealth dataset and HAR dataset
