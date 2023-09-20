# msc_aml_thesis_2023

Code associated with:
 - Automatic Exact Subspace Diffusion for Deep, Distributed, Multi-Task Learning
 - MSc Applied Machine Learning @ Imperial College London (2023)
 - Author: Shreya Wadehra

Repo contains experiments for distributed, multi-task, deep network training in the form of notebooks using PyTorch. Experiments include:
 - Approximate projection algorithm on MNIST data
 - Exact Subspace Diffusion algorithm on MNIST data
 - Exact Subspace Diffusion with Local Automatic Gradient Descent on MNIST data
 - Exact Subspace Diffusion with Shared Automatic Gradient Descent on MNIST data

 - Exact Subspace Diffusion algorithm on CIFAR-10 data
 - Exact Subspace Diffusion with Local Automatic Gradient Descent on CIFAR-10 data
 - Exact Subspace Diffusion with Shared Automatic Gradient Descent on CIFAR-10 data

Background:
 - Approximate projection algorithm [1]   [paper](https://arxiv.org/abs/1905.08750)
 - Exact Subspace Diffusion algorithm [2] [paper](https://arxiv.org/abs/2304.07358)  
 - Automatic Gradient Descent [3]         [paper](https://arxiv.org/abs/2304.05187) 

References:
 - [1] R. Nassif, S. Vlaski, and A. H. Sayed, “Adaptation and learning over networks under subspace constraints—Part I: Stability analysis,” IEEE Transactions on Signal Processing, vol. 68, pp. 1346–1360, 2020.
 - [2] S. Wadehra, R. Nassif, and S. Vlaski, “Exact subspace diffusion for decentralized multitask learning,” To appear in IEEE CDC 2023.
 - [3] J. Bernstein, C. Mingard, K. Huang, N. Azizan, and Y. Yue, “Automatic Gradient Descent: Deep Learning without Hyperparameters,” arXiv:2304.05187, 2023.