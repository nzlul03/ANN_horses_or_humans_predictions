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

## Result
|         |  Accuracy  |  F1_Score  |
|---------|------------|------------|
| Model 1 |   0.931    |   0.938    |
| Model 2 |   0.473    |   0.000    |
| Model 3 |   0.941    |   0.946    |


## Model 1 (Result)
### Loss
![image](https://user-images.githubusercontent.com/54148951/180595452-250054e1-7e7f-4169-8162-afcd9fed9795.png)
### Accuracy
![image](https://user-images.githubusercontent.com/54148951/180595459-0e809840-1553-4205-a236-17974f1da3fa.png)


## Model 2 (Result)
### Loss
![image](https://user-images.githubusercontent.com/54148951/180595470-c4380ce3-3510-4c9b-a5b8-af46e1d7a105.png)
### Accuracy
![image](https://user-images.githubusercontent.com/54148951/180595475-f767cbca-958b-4d63-9d8f-92e198840358.png)


## Model 3 (Result)
### Loss
![image](https://user-images.githubusercontent.com/54148951/180595492-8d272674-3387-4d63-a9d5-950aeac860fb.png)
### Accuracy
![image](https://user-images.githubusercontent.com/54148951/180595494-a54bbf19-459d-4821-8303-f17fbfb7720d.png)
