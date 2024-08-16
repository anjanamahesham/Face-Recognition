# Face-Recognition
Face Recognition project using ResNet-18. This project trains a deep learning model to recognize faces and make predictions on new images. It includes code for training, testing, and inference.
# Face Recognition

## Project Overview
This project implements a face recognition system using ResNet-18. The model is trained to identify faces and can make predictions on new images.

The primary goal of this project is to develop a robust face recognition system using deep learning techniques. The system is designed to accurately identify individuals based on their facial features from images. It can be used for various applications such as security, authentication, and identification in different scenarios.

Methodology
This project is built on several key components:

Data Preparation: Images of faces are preprocessed using data augmentation techniques like random cropping, resizing, and horizontal flipping to enhance the training process.

Model Architecture: The ResNet-18 architecture is utilized, with modifications to the final fully connected layer to match the number of classes (individuals) in the dataset.

Training: The model is trained using a labeled dataset of faces. Cross-Entropy Loss is employed as the loss function, and Stochastic Gradient Descent (SGD) with momentum is used for optimization.

Inference: The trained model is used to make predictions on new images, identifying the person in the image based on the learned features.

## Features
- **Model**: ResNet-18 architecture.
- **Training**: Data augmentation techniques like random cropping and horizontal flipping.
- **Inference**: Predicts the identity of a person from a new image.
- **Datasets**: Custom dataset with labeled images of individuals.

## Installation Instructions
1. Clone this repository:
   ```bash
   git clone https://github.com/anjanamahesham/Face-Recognition.git

License
This project is licensed under the MIT License. This means that you are free to use, modify, and distribute this software for both personal and commercial purposes as long as you include the original copyright notice and disclaimer. For more details, see the LICENSE file.
