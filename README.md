# PCA with a Linear Autoencoder in TensorFlow
A TensorFlow-based autoencoder for dimensionality reduction using Principal Component Analysis (PCA). The project demonstrates encoding and reconstructing signals while learning efficient latent representations.

## Overview
This project explores **Principal Component Analysis (PCA)** using a **linear autoencoder** implemented in **TensorFlow/Keras**. The model is trained to encode and reconstruct input signals while reducing dimensionality, learning optimal latent representations.

The project is divided into three main parts:
- **Generating a noisy sinusoidal signal** as input.
- **Training a linear autoencoder** to perform PCA-like transformation.
- **Visualizing reconstructed signals and learned latent representations.**

## Dataset
The project generates **synthetic sinusoidal data with noise** to simulate real-world signals requiring dimensionality reduction.

## Project Structure
### Data Generation & Preprocessing
- Creates a synthetic **sinusoidal signal with noise**.
- Normalizes and formats data for input to the autoencoder.

### Model Implementation
- Defines a **linear autoencoder** using **TensorFlow/Keras**.
- Trains the network with **Mean Squared Error (MSE) loss**.
- Encodes input data into a low-dimensional representation.

### Evaluation & Visualization
- Reconstructs signals from the learned latent space.
- Compares original and reconstructed signals using **MSE**.
- Visualizes latent representations and their effectiveness.

## Installation & Requirements
To run this notebook, you need **Python 3** and the following dependencies:

```sh
pip install tensorflow numpy matplotlib
```

## Usage
Clone the repository:

```sh
git clone https://github.com/LidanAvisar/PCA-with-Linear-Autoencoder-in-TensorFlow
cd PCA-Linear-Autoencoder
```

Open the Jupyter Notebook:

```sh
jupyter notebook "PCA with Linear Autoencoder.ipynb"
```

Run all cells to train and evaluate the autoencoder.

## Results & Analysis
The notebook visualizes:
- **Original vs. reconstructed signals**.
- **Learned latent representations**.
- **Loss trends during training**.
