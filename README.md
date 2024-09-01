# Autoencoders and GANs on Fashion MNIST

This repository contains a Jupyter notebook that replicates Chapter 17 from the book *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron. The notebook demonstrates the implementation of a **Variational Autoencoder (VAE)** and a **Generative Adversarial Network (GAN)**, both trained on the Fashion MNIST dataset.

## Overview

### Variational Autoencoder (VAE)
- A Variational Autoencoder (VAE) is a type of generative model that learns a probabilistic mapping from the input data to a latent space and back. 
- The VAE in this notebook is implemented using TensorFlow and trained on the Fashion MNIST dataset, a collection of 28x28 grayscale images of clothing items.
- The notebook includes the complete implementation of the VAE, along with code to visualize the reconstructed images and the latent space representation.

### Generative Adversarial Network (GAN)
- A Generative Adversarial Network (GAN) is a model that consists of two neural networks, a **generator** and a **discriminator**, trained in opposition to each other.
- The GAN in this notebook is a simple implementation where the generator is trained to produce images that resemble Fashion MNIST images, while the discriminator learns to distinguish between real and generated images.
- The notebook provides the implementation of the GAN, along with code to visualize the generated images at different stages of training.



4. Run the cells in the notebook to train the VAE and GAN on the Fashion MNIST dataset and visualize the results.

## Results

### VAE Reconstructions
The notebook includes visualizations of the original Fashion MNIST images alongside their reconstructions by the VAE, as well as a 2D representation of the latent space.

### GAN Generated Images
The GAN section showcases the evolution of generated images as training progresses, demonstrating how the generator improves over time in creating realistic-looking images.

## Acknowledgments

This project is based on the examples provided in Chapter 17 of *Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow* by Aurélien Géron. 
