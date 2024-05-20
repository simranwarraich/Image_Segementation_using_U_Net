# Image Segementationusing U-Net

This project focuses on image segmentation using the U-Net architecture. The code utilizes TensorFlow and the Oxford-IIIT Pet dataset for training and evaluation. The main steps involved are:

- **Setting up the Environment:** Install the required packages and import necessary libraries.
- **Loading the Dataset:** Download the Oxford-IIIT Pet dataset and preprocess the images and masks.
- **Building the Pipeline:** Create data augmentation layers, define batch sizes, and set up the training and testing pipelines.
- **Defining the Model:** Build the U-Net model using the MobileNetV2 pre-trained model as the encoder and upsampling layers for the decoder.
- **Training the Model:** Compile the model, define hyperparameters, and train the U-Net model on the preprocessed dataset.
- **Evaluating the Model:** Plot the training and validation loss curves to assess the model's performance.
- **Making Predictions:** Use the trained model to make predictions on the test dataset and visualize the results.

The code includes utility functions for displaying images, creating masks, and monitoring training progress. Additionally, it leverages TensorFlow's built-in data augmentation layers for horizontal flipping during training.
