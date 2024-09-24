## Project Overview

1. **Coloring Grey Images**
    - This project focuses on taking grayscale images as input and using a neural network model to predict their color versions. The model is trained to learn the mapping between grayscale and colored images, allowing it to generate realistic color versions of black-and-white photos.
    - Libraries used: TensorFlow, Keras, OpenCV
    - Key Steps:
        - Load and preprocess the dataset (grayscale images).
        - Build an autoencoder architecture.
        - Train the model to colorize the images by predicting color channels.
        - Evaluate and visualize the results.

2. **Denoising Autoencoder**
    - This project focuses on using a denoising autoencoder, which takes noisy images as input and attempts to reconstruct a clean version of the image. By training the network on noisy and clean image pairs, it learns to remove noise from corrupted images.
    - Libraries used: TensorFlow, Keras, OpenCV
    - Key Steps:
        - Load and preprocess the dataset (original images).
        - Add synthetic noise to the images.
        - Build a denoising autoencoder model.
        - Train the model to remove noise from the images.
        - Evaluate the denoising results.
