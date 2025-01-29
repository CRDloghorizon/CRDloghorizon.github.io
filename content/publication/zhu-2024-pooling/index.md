---
title: 'Pooling On-the-go for NoC-based Convolutional Neural Network Accelerator'
authors:
- admin
- Yizhi Chen
- Zhonghai Lu
weight: 13
date: 2024-07-01
publishDate: "2025-01-01T00:03:00Z"
reading_time: false

publication_types: ['paper-conference']

publication: '*International Conference on Embedded Computer Systems: Architectures, Modeling and Simulation (SAMOS XXIV)*'
publication_short: In *SAMOS*

abstract: Due to the complexity and diversity of deep convolutional neural networks (CNNs), Network-on-chip (NoC) based CNN accelerators have grown in popularity to improve inference efficiency and flexibility. Current optimization approaches focus on computational-heavy layers. Therefore, pooling layers are often ignored and processed individually using general processing units. In this work, we explore the acceleration of pooling layers by in-network processing. We propose a pooling on-the-go method to do the pooling operations while transmitting its prior layer outputs. Consequently, we combine the pooling layer with its prior convolution layer to remove unnecessary data movements. We demonstrate our method on a cycle-accurate NoC-CNN accelerator simulator on two CNN models, LeNet and VGG16. The results show that the processing time of individual pooling layers is almost eliminated by around 99%. Compared with the pooling standalone baseline, we can achieve 1.09x speedup in the full LeNet model, and up to 1.16x speedup in the combined layers that our approach applies.

featured: false

doi: "10.1007/978-3-031-78380-7_9"
url_pdf: ''

share: false
---
