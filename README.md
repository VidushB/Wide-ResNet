# Wide-ResNet

# Mini-Project 1: Residual Network Design (ECE-GY 7123, NYU Tandon, Spring 2022)
This repository contains code for our first mini-project of ECE-GY 7123 (Deep Learning) at NYU. All code for this project is written in pytorch.
The model was trained on the CIFAR-10 dataset under the constraint that our model must have less than 5 Million trainable parameters.

# Data
Our training data is loaded using the DataLoader class in Pytorch. Training data gets normalized and Randomly Cropped to avoid overfitting. We prepare our data using DataLoaders in Pytorch.

# Model
Our model is also implemented in Pytorch. Using Skip Connections, we build a model capable of learnign a lot of hyperparameters in a deep model while mitigating the ill-effects of vanishing and exploding gradients.

# Results
Our final model performs well on CIFAR-10s validation set, scoring an accuracy of 94.23%

# Contributors 
1. Vidush Batra (vb2184)
2. George Gao (mg 5554)
3. Neha Reddy Nelly (nn2233)
