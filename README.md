# PCOS Detection Using Ultrasound Images

## Project Overview
This project develops a deep learning model utilizing TensorFlow and Keras to classify ultrasound images for detecting Polycystic Ovary Syndrome (PCOS), distinguishing between 'infected' and 'notinfected' categories. It encompasses data augmentation, model training with early stopping, performance evaluation, and concludes with the model's preservation.

## Dataset
The dataset comprises ultrasound images categorized into 'infected' and 'notinfected', used for training, validation, and testing the model. The dataset distribution is as follows:
- Training Data: 70%
- Validation Data: 15%
- Test Data: 15%

## Model Architecture
The model is a Sequential deep learning model, consisting of convolutional and pooling layers for feature extraction, followed by dense layers for classification. The model uses the Adam optimizer and binary crossentropy loss function.

## Requirements
- Python 3.8+
- TensorFlow 2.x
- Keras
- Numpy
- Matplotlib
- Scikit-learn
