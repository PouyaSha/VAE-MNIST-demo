# Variational Autoencoder (VAE) on MNIST

This repository contains a simple PyTorch implementation of a **Variational Autoencoder (VAE)** trained on the MNIST handwritten digits dataset.  
It is designed for learning and demonstration purposes, with clear step-by-step explanations.

---

## Run in Google Colab
You can run this notebook directly in Colab without any setup:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/19nnFokSELSVI_A3ljzA6JNyym-iQyzZM?usp=sharing)

---

## Features
- Loads and preprocesses the MNIST dataset  
- Implements an Encoder and Decoder in PyTorch  
- Uses the **reparameterization trick** for sampling latent variables  
- Optimizes the **ELBO (Evidence Lower Bound)** = Reconstruction Loss + KL Divergence  
- Visualizes:
  - Reconstructed digits
  - Random samples from latent space
  - 2D latent space embeddings
  - Interpolations between digits in latent space  

---

##  Requirements
- Python 3.8+  
- PyTorch  
- Torchvision  
- Matplotlib  
- Jupyter or Google Colab  

If you run in Colab, everything is pre-installed ✅

---

## Example Results
### Reconstruction
Digits after passing through the VAE:  
![Alt text](images/reconstructed.png)


### Generating Images from Random Samples
Random Sampling from Prior p(z) = N(0, I):

![Alt text](images/random_samples.png)


### Latent Space
2D latent embeddings of MNIST digits:  
![Alt text](images/latent_space.png)


### Interpolation between two test digits
Interpolation between two test digits
![Alt text](images/interpolation.png)





---

## References
- [Kingma & Welling (2013) Auto-Encoding Variational Bayes](https://arxiv.org/abs/1312.6114)  
- [PyTorch VAE Tutorial](https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html)  
- [Karpathy Blog on RNNs (related intuition on latent spaces)](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)  

---

## Author
Made by **Pouya Shamshiri**  
Feel free to fork, open issues, or suggest improvements!  
