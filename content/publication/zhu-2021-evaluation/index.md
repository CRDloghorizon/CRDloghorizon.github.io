---
title: Evaluation of Time Series Clustering on Embedded Sensor Platform
authors:
- Wenyao Zhu
- Zhonghai Lu

date: 2021-09-01
weight: 10

publishDate: '2025-01-20T15:03:01.529464Z'
publication_types: ['paper-conference']

publication: '*2021 24th Euromicro Conference on Digital System Design (DSD)*'
doi: "https://doi.org/10.1109/DSD53832.2021.00038"

publication_short: In *DSD*

abstract: Clustering is one of the major problems in studying the time series data, while solving this problem on the embedded platform is almost absent because of the limitation of computational resources on the edge. In this paper, two typical clustering algorithms, K-means and Self-Organizing Map (SOM), together with Euclidean distance measurement and dynamic time warping (DTW) are studied to verify their feasibility on an embedded sensor platform. For the given datasets, the models are trained on a computer and moved to an ESP32 microprocessor for inference. It is found that the SOM achieves similar accuracy compared with K-means, while its inference process takes a longer time. The experiment results show that a sample with 300 data points can be clustered into 12 clusters within 40 ms by SOM with the DTW model, while the fastest model can run at around 2 ms using K-means with Euclidean distance model. In other words, it can process the data collected from 40 sensors per second in 680 ms. The clustering function can be scheduled with the realtime data acquisition and transmission tasks. The performance gathered supports that it is feasible to deploy the time series clustering model on the embedded sensor platform.

# Display this page in the Featured widget?
featured: false

url_pdf: ''
---
