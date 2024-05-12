# Image-Recognition-using-CNN

This project implements Convolutional Neural Networks (CNNs) to classify images from the CIFAR-10 dataset. The dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

## Requirements

- Python 3
- TensorFlow 2.x
- Matplotlib
- Scikit-learn
- Visualkeras

You can install the required packages using pip:

## Getting Started

1. Clone the repository:

2. Follow the instructions in the notebook to execute the code and train the models.

## Model Architectures

- **Base Model**: Simple CNN architecture with convolutional layers, max-pooling, and dense layers.
- **Model_1 with Dropouts**: Added dropout layers to prevent overfitting.
- **Model_2 with Additional Filters**: Increased model complexity by adding more convolutional layers.
- **Model_3 with Batch Normalization**: Incorporated batch normalization layers to stabilize training.

## Results

- Base Model Test Accuracy: 0.6566
- Model_1 Test Accuracy (with Dropouts): 0.7127
- Model_2 Test Accuracy (with Additional Filters): 0.7476
- Model_3 Test Accuracy (with Batch Normalization): 0.8790

## Conclusion

The project demonstrates the effectiveness of CNNs in image classification tasks, with improvements in accuracy observed through model iterations. Experimenting with different architectures and techniques such as dropout and batch normalization can further enhance model performance.
