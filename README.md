# CycleGAN: Photo to Monet Style Transfer

## 📌 Project Description
This project implements a CycleGAN model to transform photographs into Monet-style paintings.
It was developed as part of the Week 5 Project for the "Introduction to Deep Learning" course on Coursera.

## 🎯 Objective
Use Generative Adversarial Networks (GANs) to perform image-to-image translation without paired training data.

## 🛠️ Technologies Used
- Python 3.10
- TensorFlow 2.x / Keras
- NumPy, Matplotlib, PIL
- Google Colab (GPU T4)

## 📊 Dataset
- **Monet paintings:** 300 images (256x256)
- **Photographs:** 7,038 images (256x256)
- Source: Kaggle competition "I'm Something of a Painter Myself"

## 🏗️ Model Architecture
- **Generator:** Encoder-Decoder with 9 Residual Blocks + Instance Normalization
- **Discriminator:** PatchGAN with 4 convolutional layers

## 📈 Training Details
- Epochs: 10
- Loss Functions: Adversarial Loss + Cycle Consistency Loss (λ=10)
- Optimizer: Adam (lr=0.0002, β₁=0.5)

## 🎨 Results
Successfully generated 7,038 Monet-style images from photographs.
The model was trained on Google Colab with GPU T4 acceleration.

## 👤 Author
**Litim Hadjer**
Master 2 Student - Sétif, Algeria
