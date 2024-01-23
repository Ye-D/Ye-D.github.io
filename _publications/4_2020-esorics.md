---
title: "An Efficient 3-Party Framework for Privacy-Preserving Neural Network Inference"
collection: publications
permalink: /publication/4_2020-esorics
date: 2020-09-12
venue: 'European Symposium on Research in Computer Security'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-58951-6_21'
---
Authors: Liyan Shen, Xiaojun Chen, Jinqiao Shi, **Ye Dong**, and Binxing Fang

Abstract: In the era of big data, users pay more attention to data privacy issues in many application fields, such as healthcare, finance, and so on. However, in the current application scenarios of machine learning as a service, service providers require users’ private inputs to complete neural network inference tasks. Previous works have shown that some cryptographic tools can be used to achieve the secure neural network inference, but the performance gap is still existed to make those techniques practical.

In this paper, we focus on the efficiency problem of privacy-preserving neural network inference and propose novel 3-party secure protocols to implement amounts of nonlinear activation functions such as ReLU and Sigmod, etc. Experiments on five popular neural network models demonstrate that our protocols achieve about 1.2\times –11.8\times and 1.08\times –4.8\times performance improvement than the state-of-the-art 3-party protocols (SecureNN) in terms of computation and communication overhead. Furthermore, we are the first to implement the privacy-preserving inference of graph convolutional networks.