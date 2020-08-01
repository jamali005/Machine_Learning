# This Folder is my work in Machine Learning offered in Winter Semester 2019 
## miniproject : 
* Implement Spam Classifier Using Naive Bayes using the given dataset. *

## Linear Discriminant Function : 

1. Assume you have three classes. The data points for the one class are sampled from the Gaussian distribution with the mean1 [0,4], for the second class with the mean2 [3,3] and finally for the third class with the mean3 [5,1], the covariance matrix [[0.3, 0.2], [0.2, 0.2]] is the same for all three distributions.

2. Create 1000 sample for each class and visualise them.

3. Implement least-square classification in matrix notation.

4. Using your implementation find and visualise the decision boundary using
a) Any of two given datasets, simply two class classification. Show the behaviour of the decision boundary in case of outliers (see how it is demonstrated in the slide 25)
b) All three given datasets.

## Assignement 5: 

1. Read the project description given in pdf-file

2. Load and understand the feature values in excel-file

3. Visualise features for each individual pen-type (either use differen colores or sub-figures)

4. Learn the classification model using one or more of known techniques

5. Analyse the results

## Assignement AdaBoost:

Use AdaBoost to classify IRIS dataset.

1. download dataset

from sklearn import datasets

iris = datasets.load_iris()

2. train and evaluate adaboost model

3. use different weak classifiers 

4. evaluate and compare the accuracy for the Adaboost with different weak classifiers

## Assignement 7

1.

a. Use Decision Tree for the classification of IRIS dataset

b. Visualize this Decision Tree

2. 

a. Apply Random Forest and Extremly Randomised Trees to DT_dataset dataset 

b. Feature 'actual' denotes labels of the dataset

## Assignement 10 (Neural Network 1): 

Implement a neural network to recognize handwritten digits from MNIST dataset.

- Download MNIST dataset. Visualise it.

- Constract a network which has

   3 layers

   * an input layer (since image has size 20x20 you will have 400 input values)

   * a hidden layer with 25 nodes 

   * an output layer with 10 classes (corresponding to the 10 digits)

- Implement feedforward propagation for this neural network to predict handwritten digits 

- Implement the backpropagation algorithm to learn the parameters for the network. Use cross-entropy loss function without regularization.

Note: for the simplicity recode the labels as vectors containing only values 0 or 1.

## Assignement 12 (Neural Network 2):

Build a simple network with one hidden layer and apply it to MNIST dataset.

Input size is 28x28=784, Hidden layer size is 100 and output layer size is 10. Loss function is cross-entropy

a) Compare training of this data set using (i) batch learning, (ii) stochastic learning and (iii) mini-batch learning

b) Vary the learning rate value and visualise the convergence of the loss function

c) Implement Momentum - visualise results

