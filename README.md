# msc_aml_thesis_2023

Code associated with:
 - Automatic Exact Subspace Diffusion for Deep, Distributed, Multi-Task Learning
 - MSc Applied Machine Learning @ Imperial College London (2023)
 - Author: Shreya Wadehra

Repo contains experiments for distributed, multi-task, deep network training in the form of notebooks using PyTorch. Experiments include:
 - Approximate projection algorithm on MNIST data
 - Exact Subspace Diffusion algorithm on MNIST data (Algorithm 1)
 - Exact Subspace Diffusion with Local Automatic Gradient Descent on MNIST data (Algorithm 2)
 - Exact Subspace Diffusion with Shared Automatic Gradient Descent on MNIST data (Algorithm 3)

 - Exact Subspace Diffusion algorithm on CIFAR-10 data (Algorithm 1)
 - Exact Subspace Diffusion with Local Automatic Gradient Descent on CIFAR-10 data (Algorithm 2)
 - Exact Subspace Diffusion with Shared Automatic Gradient Descent on CIFAR-10 data (Algorithm 3)

Abstract:
>This thesis proposes and implements three algorithms for the case of subspace-constrained, distributed, multi-task optimization. Algorithm 1 extends primal-dual optimization techniques to a
distributed, multi-task, and subspace-constrained setting to remove a bias seen in penalty-based
algorithms. The following two algorithms apply specifically to neural network optimization. Algorithm 2 combines Algorithm 1 and automatic gradient descent to establish an automatic learning
rate as a function of an agent’s local gradient. Algorithm 3 improves upon this by calculating the
automatic learning rate using shared gradients amongst the neighboring agents. The algorithms
were then implemented in PyTorch and tested on MNIST and CIFAR-10 data. Results show that
Algorithm 1 effectively removed the bias seen in penalty-based optimization, Algorithms 2 and 3
was successfully able to train with no manual learning rate tuning, and Algorithm 3 provided an
improvement in convergence over Algorithm 2 resulting from the shared gradients.

Background:
 - Approximate projection algorithm [1]   [paper](https://arxiv.org/abs/1905.08750)
 - Exact Subspace Diffusion algorithm [2] [paper](https://arxiv.org/abs/2304.07358)  
 - Automatic Gradient Descent [3]         [paper](https://arxiv.org/abs/2304.05187) 

References:
 - [1] R. Nassif, S. Vlaski, and A. H. Sayed, “Adaptation and learning over networks under subspace constraints—Part I: Stability analysis,” IEEE Transactions on Signal Processing, vol. 68, pp. 1346–1360, 2020.
 - [2] S. Wadehra, R. Nassif, and S. Vlaski, “Exact subspace diffusion for decentralized multitask learning,” To appear in IEEE CDC 2023.
 - [3] J. Bernstein, C. Mingard, K. Huang, N. Azizan, and Y. Yue, “Automatic Gradient Descent: Deep Learning without Hyperparameters,” arXiv:2304.05187, 2023.
