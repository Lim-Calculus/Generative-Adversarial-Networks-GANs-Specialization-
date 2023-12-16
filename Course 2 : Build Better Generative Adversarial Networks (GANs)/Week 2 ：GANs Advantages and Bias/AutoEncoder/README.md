## Variational Autoencoder (VAE)
<br>
- The "AE" in VAE stands for autoencoder. As an autoencoder, the VAE has two parts: an encoder and a decoder. Instead of mapping each image to a single point in  𝑧
 -space, the encoder outputs the means and covariance matrices of a multivariate normal distribution where all of the dimensions are independent. You should have had a chance to read more about multivariate normal distributions in last week's assignment, but you can think of the output of the encoder of a VAE this way: the means and standard deviations of a set of independent normal distributions, with one normal distribution (one mean and standard deviation) for each latent dimension.<br>
<br>
- The encoding outputs a distribution in 𝑧-space, and to generate an image you sample from the distribution and pass the 𝑧-space sample to the decoder, which returns an image.
