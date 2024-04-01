# Face_Expression_Recognizer-with-CNN
Face Expression Recognition using Convolutional Neural Networks

Overview
This repository contains code for training and evaluating two Convolutional Neural Network (CNN) models for facial expression recognition. The models are trained using Keras Sequential API and evaluated on a separate test dataset. Key steps include data preparation, model architecture design, training, evaluation, and comparison.


Key Features
Data Preparation: Organized image data into training, validation, and test sets using the splitfolders library. Preprocessed images by resizing, normalizing pixel values, and applying data augmentation techniques.
Model Architecture: Designed two CNN architectures with convolutional layers, batch normalization, max-pooling layers, and fully connected layers. Dropout regularization applied for preventing overfitting.
Model Training: Trained both models using prepared data, with a batch size of 32 and for 30 epochs. Monitored accuracy and loss on training and validation sets during training.
Model Evaluation: Evaluated models on a separate test dataset and computed the AUC score. Visualized confusion matrix for assessing model performance across different classes.
Model Comparison: Compared the performance of the two models based on training/validation accuracy and loss.
Model Saving: Saved both trained models for future use.
