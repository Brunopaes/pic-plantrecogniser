# plantRecogniser - A Neural Network Aproach #

This Artificial Neural Network was developed in Java 1.8 for recognise, based on inputs, plants of the family _Iris_.

-----------------------------------------------

## Inputs ##

The input layer has __4__ nodes and accept this following normalized values:

* 1. sepal length in cm 
* 2. sepal width in cm 
* 3. petal length in cm 
* 4. petal width in cm 

_Obs¹: You can find the input values at the data folder_

----------------------------

## Structure ##

You can find at the paes.sigmoid.training the training algorithm. At this file we have the propagation and the backpropagation, and the goal of this archive is to achieve the best Layer's weights.

### Variables ###

* int n = 3 - _This variable is responsible for the number of neurons in the hidden layer;_
* int minValue = 0 - _This variable is responsible for control the input's matrix;_
* int age = 1 - _This variable is responsible for count the number of ages;_

_Obs²: 1 age is equals 120 iterations_

---------------------------------------

## Outputs ##

The output layer has __3__ nodes. The following combination represents one of the three plants of the family _Iris_.

* _Iris-Setosa_: 0 0 1;
* _Iris-Versicolor_: 0 1 0;
* _Iris-Virginica_: 1 0 0.

----------------------------

## Activation Functions and Coeficient Gradient ##

__Sigmoid Function:__
* f(x) = 1/(1 + Math.exp(-x))

--------------------------------------------------


## References Links ##

The sample repository:
* <https://archive.ics.uci.edu/ml/datasets/iris/>

--------------------------------------------------

