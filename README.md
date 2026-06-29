# Cat vs Dog Image Classification using CNN
An image classification project using a Convolutional Neural Network (CNN) to distinguish between cats and dogs. Developed in Python with TensorFlow, featuring data augmentation and custom layers to optimize accuracy.
## Project Overview
This project uses a Convolutional Neural Network (CNN) to classify images as either a cat or a dog. The model is trained using TensorFlow and Keras and learns image features automatically to perform binary image classification.

## Objective
The objective of this project is to build a deep learning model that can accurately distinguish between cat and dog images.

## Dataset
- Dataset: Cats vs Dogs
- Classes:
  - Cat
  - Dog
- Images are preprocessed by resizing and normalizing before training.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV (optional)

## Project Workflow
1. Load the dataset.
2. Preprocess the images.
3. Build the CNN model.
4. Train the model.
5. Evaluate model performance.
6. Predict the class of new images.

## CNN Architecture
- Convolutional Layers
- ReLU Activation
- Max Pooling Layers
- Flatten Layer
- Dense Layers
- Sigmoid Output Layer

## Evaluation Metrics
- Accuracy
- Loss
- Validation Accuracy
- Validation Loss

## Results
The CNN model successfully classifies images into cats and dogs with good accuracy. Training and validation performance are monitored using accuracy and loss curves.

## Future Improvements
- Apply Data Augmentation
- Use Transfer Learning (MobileNetV2, VGG16, ResNet50)
- Hyperparameter Tuning
- Increase Dataset Size
- Deploy the model using Flask or Streamlit
