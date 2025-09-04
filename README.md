# Spiking Neural Networks on MNIST with Whetstone and Fugu

This project demonstrates how to build, train, and simulate **spiking neural networks (SNNs)** using the [Whetstone](https://github.com/NeuromorphicComputing/whetstone) training methodology and [Fugu](https://github.com/neuromorphs/fugu), a platform-agnostic simulation tool for neuromorphic computing.

We apply these tools to the **MNIST dataset**, converting standard neural networks (dense and convolutional) into spiking equivalents and simulating them in a way that is compatible with neuromorphic hardware.

---

## Overview

This repository contains a Jupyter notebook that:
- Loads and pre-processes the MNIST dataset.
- Defines and trains several Tensorflow/Keras-based architectures (MLPs, CNNs).
- Converts trained models into spiking networks using Whetstone package.
- Simulates the spiking models using a manually included version of the Fugu framework.
- Evaluates classification performance in the spiking domain.

---

## Colab Usage

The recommended way to use this project is via **Google Colab**. This avoids the need to install dependencies locally and provides GPU acceleration.

### Run in Colab:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yourusername/your-repo-name/blob/main/notebooks/SNN_MNIST_Whetstone_Fugu.ipynb)

> **Note:** Dependencies for Fugu and Whetstone have been included by directly copying the necessary source code into the notebook or repository, rather than using `pip install`. This improves compatibility and avoids external versioning issues, especially in Colab environments.
