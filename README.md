# FRUIT-CLASSIFIER
This project involves building a fruit classification model using deep learning techniques. The goal is to classify images of different fruits into their respective categories based on features extracted by a Convolutional Neural Network (CNN). Here’s a brief breakdown of the project:

Project Description:
Dataset: The project uses the Fruits 360 dataset, which contains images of various fruits, organized into different categories. The dataset is divided into training and testing sets, with labeled images.

Data Preprocessing:

Image Resizing: All images are resized to a uniform size of 100x100 pixels.
Normalization: Pixel values are normalized to the range [0, 1] to help the model learn effectively.
Model Architecture: A Convolutional Neural Network (CNN) is used for classification. It consists of several convolutional layers for feature extraction, followed by pooling layers and a fully connected output layer to predict the class.

Training and Evaluation:

The model is trained on the training set using the ImageDataGenerator class from Keras for real-time data augmentation.
The model is then evaluated on the test set to assess its accuracy.
Prediction: Once the model is trained, it can predict the class of new fruit images. The system displays both the input image and the predicted class.

Deployment:

The model is saved in the Keras native format (.keras) for later use.
Users can upload an image, and the model will classify it and display the predicted fruit class.
Key Features:
Image Augmentation: For better generalization, images are augmented during training.
Real-time Prediction: After training, the model can classify new images and show the results.
Interactive Visualization: The system shows the input image alongside the predicted result for clarity.
This project demonstrates how deep learning can be applied to real-world image classification problems, with practical applications in areas such as agriculture, food identification, or inventory management.
