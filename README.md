# Artificial Neural Networks for Horse or Human Prediction

Coding assignments of the Advanced Machine Learning Courses (2022) - University of Indonesia

## Dataset
The dataset used in this assignment is from: https://www.tensorflow.org/datasets/catalog/horses_or_humans
![feature importance](https://github.com/nzlul03/ANN_horses_or_humans_predictions/blob/f217511a7eed4ac6c0ce0b816c920cbbf1a098d9/check_dataset.png)

## Hyperparameter
- Optimizer = Adam (learning rate=0.001)
- Loss = Cross Entropy
- Activation Function = ReLu
- Batch Size = 32
- Epoch = 50

## Model
In this assignment 3 combination models will be used:
|         | Hidden Layer |        Neuron        |
|---------|--------------|----------------------|
| Model 1 |       3      |     (32, 64,128)     |
| Model 2 |       4      |   (16, 32, 64, 128)  |
| Model 3 |       5      |  (8, 16, 32, 64, 128)|



