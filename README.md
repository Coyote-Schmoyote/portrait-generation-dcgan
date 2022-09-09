# Image generation with GAN

This notebook looks into the process of generating art portraits using GAN. The project is inspired by the AI-generated portrait of Edmond de Belamy (2018) that was sold at Christie's for $432,000.

## 1. Problem Definition

Generate new images based on the input images from the art portraits.

## 2. Data

The data used in this project is the combination of Portrait Paintings dataset (https://www.kaggle.com/datasets/deewakarchakraborty/portrait-paintings) and Art Portraits dataset (https://www.kaggle.com/datasets/karnikakapoor/art-portraits), both available on Kaggle. The Portrait Painting dataset consists of 5734 images, and Art Portraits dataset consists of 4117 images.

## 3. Approach

For this project, we will take the following approach:

Import the tools
Clean the dataset
Explore and process the images
Build Discriminator and Generator, and combine them into a GAN model
Describe the training steps
Train the model
Display the result (generated portraits)

## 4. Evaluation

There is no function to evaluate the performance of a GAN model, which means that the performance of the model will be evaluated based on the quality of the generated images.
