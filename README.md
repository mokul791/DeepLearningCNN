## Deep Learning: Convolutional Neural Network (CNN) for image classification
Convolutional Neural Network in python tensorflow for classification with Fashion MNIST dataset
Collaboration: Md Ismail Alam Mokul and Shadman Raihan
(python, tensorflow, keras, scikitlearn, pandas)

- Basic CNN
  - 2 convolutional layer each followed by a Maxpool and dropout layer
  - 1 Flatten layer
  - 2 dense layer
  - Relu and softmax for activation
  - Adam optimizer
  - Early stopping was used to overcome
  - overfitting
 
- Tuned CNN
- Data Augmentation
  - New training images were created using ImageDataGenerator
  - Rotation, width shift, height shift horizontal flip were used for new image creation
- Autoencoder
  - Encoder and decoder were defined using convolutional layer, maxpooling layer, batch normalization, upsampling layer
  - Classification model was built using encoder followed by a dense layer
  - Early stopping was used to overcome overfitting
- VGG 16
  - Weights of the model was taken from imagenet
  - Adam optimizer was used
  - Early stopping was used to overcome overfitting





