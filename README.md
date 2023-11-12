# Artistic Style Transfer in TensorFlow

This project implements an artistic style transfer algorithm, which merges two images, namely a "content" image and a "style" image, to create a generated image that looks like the content image but painted in the style of the style image.

## Project Overview

The Jupyter Notebook in this repository demonstrates the entire process of the style transfer, including data preprocessing, the building of the neural network model, the training process, and the evaluation of the results.

## Key Terms

Before proceeding, here are some key terms related to neural style transfer that will be helpful to understand:

- **Content Image**: The image that will retain its original content but adopt a new style.
- **Style Image**: The image that provides the artistic style which will be applied to the content image.
- **Generated Image**: The result of applying the style onto the content image.
- **Convolutional Neural Network (CNN)**: A deep learning algorithm that can take an input image, assign importance to various aspects/objects in the image, and differentiate one from the other.
- **VGG19**: A variant of the VGG model which consists of 19 layers. It's often used in style transfer for its simplicity and robustness.
- **Loss Functions**: Mathematical functions that measure the difference between the current image and the goal; used to guide the transformation process.
- **Optimizer**: An algorithm or method used to change the attributes of the neural network such as weights and learning rate in order to reduce the losses.

## Setup Instructions

Follow these steps to set up and run the style transfer model on your local machine.

### Prerequisites

You need to have Python 3.6 or higher installed along with the following packages:

- TensorFlow 2.x
- NumPy
- Matplotlib
- PIL (Pillow)
