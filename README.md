# Ahmet-Dikbayir-Portfolio
My portfolio
# [Project 1: Brain Tumor Detection Convolutional-Neural-Network-with Functional-API](https://github.com/AhmetDikbayir/Convolutional-Neural-Network-with-Functional-API)

I used Brain Tumor Dataset where I downloaded from Kaggle. There were two different folder one of them tumor positive images and other one is tumor negative images. All dataset had 278 images half of them is true and others negative. I built Convolutional Neural Network (CNN) with Functional API. The model had 1 input 10 hidden 1 output layers. To prevent the overfitting 3 times was used drop, and 2 times Batch Normalization. In the hidden layer Relu activation function was used, and softmax used in the output layer. When compiling model, Categorical Cross Entropy used as a loss function, Adamax used as an optimizer, and accuracy used as a metric. I apply 40 epochs and 128 batch size in this model. As a result, model training dataset accurcy is 1 and test dataset accuracy is 0.71.

# [Project 2: Image Classification using MNIST Fashion Dataset](https://github.com/AhmetDikbayir/Neural-Network-Project-with-MNIST-Fashion-Dataset)

I used MNIST Fashion Dataset in this project. Fashion-MNIST is a dataset of Zalando's article images—consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28x28 grayscale image, associated with a label from 10 classes. Zalando intends Fashion-MNIST to serve as a direct drop-in replacement for the original MNIST dataset for benchmarking machine learning algorithms. It shares the same image size and structure of training and testing splits.

I used Keras Sequential Model in this project. I used ReLU activation function, and 10 output layers. I tried my model with 10 iterations, so as a result of this iterations my model accuracy score was 0.91.

After that I tried my model with 20 iterations and lastly my model accuracy score increased 0.93.
