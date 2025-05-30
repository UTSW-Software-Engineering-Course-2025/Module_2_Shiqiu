# Observation of the Hyperparameter Grid Search Results:
I trained models for 40 epochs, exploring both model structure and two hyperparameters:

Latent dimensions: 32, 64, 128

Learning rates: 1e-4, 1e-5, 1e-6

Key findings:

All configurations achieved high classification accuracy (>99%).

cGAN model is less stable than cVAEcGAN model

Learning rate 1e-4 consistently produced the best reconstructions across all latent dimensions. This suggests that 1e-5 and 1e-6 may not have converged within 40 epochs.

The impact of latent dimension size on reconstruction quality was not clearly observable. However, differences may emerge in the structure of the latent space, warranting further analysis.
