# Generative Modeling

This folder contains implementations of advanced generative modeling algorithms: **Variational Autoencoder (VAE)** and **Generative Adversarial Network (GAN)**. These models learn the underlying data distribution to generate new, realistic data samples.

---

## Included Algorithms

### 1. **Variational Autoencoder (VAE)**

- **Description**:
  - A Variational Autoencoder (VAE) encodes input data into a latent space and decodes it back to reconstruct the original data with added variability. The model uses the reparameterization trick to enable gradient-based optimization.
- **Features**:
  - Trained on the MNIST dataset for image reconstruction and generation.
  - Incorporates a probabilistic latent space to generate new samples.
  - Includes custom loss functions combining reconstruction loss (binary cross-entropy) and KL divergence.
- **Notebook**: [`VAE_Complete.ipynb`](./VAE_Complete.ipynb)

---

### 2. **Generative Adversarial Network (GAN)**

- **Description**:
  - A Generative Adversarial Network (GAN) consists of two competing neural networks, a generator and a discriminator, that learn to produce realistic data by refining synthetic samples.
- **Features**:
  - Generator creates synthetic images from random noise.
  - Discriminator evaluates whether images are real or fake.
  - Trained on the MNIST dataset to generate realistic handwritten digits.
- **Notebook**: [`GAN Complete.ipynb`](./GAN%20Complete.ipynb)

---

## How to Use

1. **Open the desired notebook**:

   - [`VAE_Complete.ipynb`](./VAE_Complete.ipynb)
   - [`GAN Complete.ipynb`](./GAN%20Complete.ipynb)

2. **Run the cells sequentially**:

   - Data loading and preprocessing.
   - Model definition and training.
   - Evaluation and visualization of generated samples.

3. **View results**:
   - For VAE: Visualize reconstructed and generated samples from the latent space.
   - For GAN: Observe progressively realistic samples created by the generator during training.

---

## Results

### Variational Autoencoder (VAE):

- Generates diverse samples by sampling from the learned latent space.
- Produces reconstructions of input images with slight variability.

### Generative Adversarial Network (GAN):

- Produces realistic handwritten digits from random noise.
- Demonstrates the adversarial training process between generator and discriminator.

---

## References

- **VAE**: _Kingma and Welling. Auto-Encoding Variational Bayes._ [Paper](https://arxiv.org/abs/1312.6114)
- **GAN**: _Goodfellow et al. Generative Adversarial Networks._ [Paper](https://arxiv.org/abs/1406.2661)
