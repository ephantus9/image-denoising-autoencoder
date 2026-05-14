# Image Denoising Using Convolutional Autoencoder

## Project Overview
This project uses a convolutional autoencoder to remove noise from images. The model learns to reconstruct clean images from noisy image inputs using the BSDS500 dataset.

## Dataset
The project uses the BSDS500 image dataset. Images are resized and normalized before being passed into the model.

## Methodology
1. Load and preprocess images.
2. Add synthetic noise to clean images.
3. Train a convolutional autoencoder.
4. Reconstruct denoised images.
5. Evaluate the results using visual comparison and image quality metrics.

## Model
The model is based on a convolutional autoencoder architecture with:
- Encoder layers for feature extraction
- Decoder layers for image reconstruction
- Mean Squared Error loss for training

## Evaluation Metrics
The project evaluates performance using:
- Mean Squared Error  
- Peak Signal-to-Noise Ratio  
- Structural Similarity Index  

## Tools Used
- Python
- PyTorch
- NumPy
- Matplotlib
- scikit-image
- Google Colab

## Results
The model shows that convolutional autoencoders can effectively reduce image noise while preserving important image structures.
