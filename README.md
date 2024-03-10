# autoencoder

Here I generate a toy dataset which exhibits a Gaussian trend that basically reflects the characteristics of solar radiation on a sunny day with clear sky conditions. The power generation in the PV system will be proportional to the radiation falling on the PV panel. As a result, the PV system's power generation will follow a Gaussian trend (indicated by the theoretical power). 

However, due to the presence of some faults, the experimental power will not follow the same trend (as indicated by the measured power).

In this exercise, I detect anomalies or faults using an autoencoder model applied to the measured power data points. 

Note: The autoencoder model for anomaly detection can be expanded to handle multi-feature and more complex patterns in real-world datasets, such as real PV panel datasets.


