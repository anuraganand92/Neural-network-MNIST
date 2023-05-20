## Fully Connected Feedforward Neural Networks for Digit Classification on MNIST Dataset

### Project Description

This project focuses on building and comparing **fully connected feedforward neural networks** for **digit classification on the MNIST dataset**. The MNIST dataset is a popular benchmark dataset in the field of machine learning and computer vision, consisting of handwritten digits.

The project involves implementing two setups of the **neural network architecture**, each with **10 hidden layers**, and **10 neurons in each layer**. The activation function used in the first setup is **sigmoid** throughout the network, while the second setup uses the **ReLU** activation function in all layers except the output layer, which uses **sigmoid**.

The networks will be trained using the **ADAM optimizer**, with a batch size of 64, learning rate of 0.0001, and the error function will be cross entropy. Batch normalization will also be applied to improve the training performance.

The trained models will be evaluated on both the training set and the test set provided in the following link: [MNIST Dataset](http://yann.lecun.com/exdb/mnist/). Performance metrics such as accuracy and loss will be computed and compared between the two network setups.

### Project Steps

1. **Data Loading**: Download and preprocess the MNIST dataset, including both the training and test sets.

2. **Neural Network Architecture**: Implement two fully connected feedforward neural networks with 10 hidden layers and 10 neurons per layer. The first setup uses the sigmoid activation function, while the second setup uses ReLU activation for hidden layers and sigmoid activation for the output layer.

3. **Model Training**: Train both neural network models using the ADAM optimizer, with a batch size of 64, learning rate of 0.0001, and batch normalization. Monitor the training process by tracking the loss and accuracy on the training set.

4. **Model Evaluation**: Evaluate the trained models on both the training set and the test set. Compute and compare performance metrics such as accuracy and loss for each network setup.

5. **Performance Comparison**: Analyze and compare the performance of the two network setups based on the evaluation results. Identify the strengths and weaknesses of each setup in terms of digit classification accuracy.
