Deep Learning (D6421) - Generative Models

Author

Nama: Giovan Prilsky Wongso

NIM: 2802463812

Kelas: LB01

Project Title

Empirical Comparative Study of Generative Models: Vanilla Autoencoder, Sparse Autoencoder, Variational Autoencoder (VAE), Generative Adversarial Network (GAN), Deep Convolutional GAN (DCGAN), and Denoising Diffusion Probabilistic Model (DDPM) with Theoretical and Empirical Proof of MLP Classifier Limitations for Image Generation.



Dataset

Fashion-MNIST



70,000 grayscale images

Image size: 28 × 28

10 fashion categories

Implemented Models

Discriminative Model

MLP Classifier (784 → 256 → 64 → 10)

Generative Models

Vanilla Autoencoder

Sparse Autoencoder

Variational Autoencoder (VAE)

Generative Adversarial Network (GAN)

Deep Convolutional GAN (DCGAN)

Denoising Diffusion Probabilistic Model (DDPM)

Evaluation Metrics

Reconstruction Metrics

Mean Squared Error (MSE)

Peak Signal-to-Noise Ratio (PSNR)

Structural Similarity Index (SSIM)

Classification Metrics

Accuracy

Qualitative Analysis

Reconstruction Comparison

Random Sampling

Latent Space Interpolation

MLP Limitation Proof

Experimental Results

Model	MSE	PSNR	SSIM

Vanilla AE	0.009214	21.3000	0.7717

Sparse AE	0.008950	21.4411	0.7723

VAE	0.017131	18.2566	0.6544

MLP Test Accuracy:



88.87%

Repository Structure

.

├── generative\_models.ipynb

├── README.md

├── requirements.txt

├── laporan.pdf

│

└── figures/

&#x20;   ├── Figure1\_Reconstruction.png

&#x20;   ├── Figure2\_\*.png

&#x20;   ├── Figure3\_MLP\_Proof.png

&#x20;   ├── Figure4\_\*.png

Installation

pip install -r requirements.txt

Running

Open:



tugasDeepLearningGAN.ipynb

and run all cells sequentially.



AI Usage Declaration

Artificial Intelligence was used as an assistive tool for concept clarification, code debugging, report structuring, and academic writing assistance. All model implementation, training, experimentation, evaluation, result verification, and final conclusions were conducted and validated by the author.

