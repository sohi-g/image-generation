# GENERATIVE AI - Image Generation
# Dogs Image Generation Using GAN & C-GAN

This project demonstrates the generation of dog images using Generative Adversarial Networks (GANs) and Conditional GANs (C-GANs). The GAN architecture allows us to train a generator network to create new images that closely resemble a given training dataset. The C-GAN model extends this concept by conditioning the generation process on additional input data, such as class labels.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Training](#training)
- [Generated Images](#generated-images)
- [Conclusion](#conclusion)

## Introduction

This project explores the use of GANs and C-GANs for generating dog images. GANs consist of two main components: a generator and a discriminator. The generator network learns to generate new images that resemble the training data, while the discriminator network learns to distinguish between real and generated images. Through adversarial training, the generator and discriminator networks improve their performance iteratively.

In the case of C-GANs, the generation process is conditioned on additional input data, which helps control the output. In this project, we use class labels as the conditioning information, enabling us to generate images of specific dog breeds.

## Dataset
Dataset comprises of ~20K dog images and 120 different breed categories.
Source: https://www.kaggle.com/competitions/generative-dog-images/data

## Training

To train the GAN and C-GAN models, follow these steps:

1. Prepare the dataset by organizing the dog images into appropriate folders according to their class labels.
2. Define the architecture of the generator and discriminator networks.
3. Set the hyperparameters for training, such as learning rate, batch size, and number of epochs.
4. Train the GAN or C-GAN models using the prepared dataset and the defined architecture.
5. Monitor the training progress, including the loss values of the generator and discriminator networks.

## Generated Images

Once the training is complete, you can generate new dog images using the trained models.

The generated images can be seen the epochs runs, allowing you to review and analyze the results every specified epcoh. Keep in mind that the quality and realism of the generated images may vary depending on the training process and the diversity of the dataset used.

## Conclusion

The Dogs Image Generation Using GAN & C-GAN project demonstrates the application of generative models to generate realistic dog images. By leveraging the power of GANs and conditioning the generation process using class labels, we can generate diverse and breed-specific dog images. This project serves as a starting point for further exploration and experimentation with GANs and C-GANs in image generation tasks.

Feel free to modify and extend this project to suit your specific requirements and explore other image generation applications using GANs and C-GANs. Happy generating!
