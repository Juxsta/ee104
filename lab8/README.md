This project creates a Convolutional Neural Network capable of predicting image classifications with an accuracy of %90+. 

In order to run this project a working tensorflow installation must be used. This can be setup with the provided Dockerfile or google collab may also be used.

This project uses 4 different CNN model.
The base model is based on the Tensorflow CNN tutorial based on the CIFAR-10 dataset. 
Imporvements are made incrementally as follows:
*  Dropout is introduced to prevent overfitting
*  Data Augmentation is introduced to increase the sample size
*  Batch Normalization is used to standardize weights between runs
*  Tensorflow's B7 EfficientNet layer is used to improve the base Convolutional Neural Network 

The base model is capable of achieving about 70% accuracy on the CIFAR-10 dataset while the data augmentation and batch normalization increase this value to about 80%. With enough training the EfficientNet model is capable of reaching up to 90% accuracy.