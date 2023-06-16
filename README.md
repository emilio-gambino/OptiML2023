# EPFL Spring 2023 - Optimization for Machine Learning: Stochastic Gradient Quantization : Saving Bandwidth in Distributed Learning

This is the code repository our CS-439 project. For this project, we decided to investigate the effects of gradient quantization on convergence in distributed learning problems. We have provided a report which explains our experiments and contains our findings. We have also provided all the code needed to reproduce our results. See below for each individual case.

# Abstract

With the ever-increasing size of machine learning
models, and with the development of scale-out architectures,
distributed learning has become crucial to exploit the benefits
of parallelism. Stochastic Gradient Descent (SGD) is naturally
suited for this task as it can leverage the distribution of data.
However, the necessary exchange of gradients among workers
leads to bandwidth limitations becoming a new performance
bottleneck. Quantized SGD (QSGD) addresses this issue through
quantization of gradients before their exchange. This report aims
to analyze the practical effects on convergence of such lossy
compression schemes.


## AlexNet

To run the models, you can run the provided notebook sequentially. This will first recompute and test the baseline model (32 bits), then 8, 4 and 2 bits quantized training.


## ResNet50


## ResNet18
