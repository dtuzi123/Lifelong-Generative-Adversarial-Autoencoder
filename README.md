# Lifelong-Generative-Adversarial-Autoencoder


# Lifelong Generative Adversarial Autoencoder

>📋 This is the implementation of Lifelong Generative Adversarial Autoencoder

# Title : Lifelong Generative Adversarial Autoencoder

# Paper link : 

# Abstract
Lifelong learning describes an ability that enables humans to continually acquire and learn new knowledge without forgetting. This capability, common to humans and animals, has lately been identified as an essential function for an artificial intelligence system aiming to learn information continuously during a certain period of time. However, modern neural networks suffer from degenerated performance when learning multiple domains sequentially, and fail to recognize past learnt tasks after being retrained. This corresponds to catastrophic forgetting and is ultimately induced by replacing the parameters associated with previously learnt tasks with new values. One popular approach in lifelong learning is the Generative Replay Mechanism (GRM) that trains a powerful generator as the generative replay network, implemented by a Variational Autoencoder (VAE) or Generative Adversarial Networks (GANs). In this paper, we study the forgetting behaviour of GRM-based learning systems by developing a new theoretical framework in which the forgetting process is expressed as an increase in the model's risk during the training. The proposed theoretical analysis indicates that the quality of generative replay samples plays an important role for performance. Although many recent attempts have provided high-quality generative replay samples by using GANs, they are limited to mainly downstream tasks due to the lack of inference. Inspired by the theoretical analysis and by the desire to address the drawbacks of existing approaches, we propose a novel lifelong learning approach, namely the Lifelong Generative Adversarial Autoencoder (LGAA). LGAA consists of a generative replay network and three inference models, each addressing the inference of a different type of latent variable. We also propose a novel lifelong learning algorithm that trains a robust generative replay network by using adversarial learning in a self-supervised manner while enforcing the inference models to capture data generative factors across domains. The experimental results show that LGAA learns novel visual concepts without forgetting and can be applied to a wide range of downstream tasks.

# Environment

1. Tensorflow 2.1
2. Python 3.6

# Training and evaluation

>📋 Python xxx.py, the model will be automatically trained and then report the results after the training.


# Visual results

>📋 MNIST to Fashion, real testing samples, reconstructions and generations

![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MNISTtoFashion_real.png) ![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MNISTtoFashion_reco.png) ![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MyMNISTtoFashion19.png)

>📋 MNIST to SVHN, real testing samples, reconstructions and generations
![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MNISTtoSVHN_real.png) ![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MNISTtoSVHN_real.png) ![image](https://github.com/dtuzi123/Lifelong-Generative-Adversarial-Autoencoder/blob/main/MNISTtoSVHN_reco.png)


# BibTex
>📋 If you use our code, please cite our paper as:


