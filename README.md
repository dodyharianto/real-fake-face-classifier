# Overview

Image generators show excellent results in producing highly realistic images, widely known as deepfakes, and have raised concern in trustworthiness such as fake news and reputation damage. 
Analyze the performance of ViT-based models (Vision Transformer, Cross-Covariance Image Transformer, and Data-Efficient Image Transformer) in classifying real and fake human faces, and evaluate the models based on metrics: accuracy, precision, recall, and F1 score.

# Dataset

This project uses the following dataset:
OpenForensics: Large-Scale Challenging Dataset For Multi-Face Forgery Detection And Segmentation In-The-Wild (Le et al., 2021).

The dataset has 44,097 training images, 7,308 validation images, and 18,895 test images, before any data preprocessing. Real images are obtained from Google Open Image. Fake images are obtained modifying facial latent vector with random values, blended into original images using Generative Adversarial Networks (GAN) models.
The images are cropped to ensure there is 1 person or face per image.

<img width="750" height="563" alt="image" src="https://github.com/user-attachments/assets/5c395dac-8eaa-4625-8c04-16f65d472467" />


Sample cropped faces:

<img width="125" height="500" alt="image" src="https://github.com/user-attachments/assets/a87b53e4-f7c4-4d3c-97ef-0e13598bf7b1" />


# Workflow

<img width="1609" height="517" alt="image" src="https://github.com/user-attachments/assets/3dfc34fc-d100-4460-aa7b-9ea1ef854437" />
