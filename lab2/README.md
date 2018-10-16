# Lab 2 - RBF Neural Networks and Self-Organizing Maps

## RBF Neural Network
The first part of this lab (file 3.1) is an implementation of a single layer Neural Network, enhanced through the use of Radial Basis Functions in order to be able to catch non-linear patterns in the input data. See [file 3.1](https://github.com/philipclaesson/ANNDA/blob/master/lab2/3.1%20RBF.ipynb) for implementation and evaluation.


## Self-Organizing Maps
The second part of this lab is an implementation of Self-Organizing Maps. SOMs make use of binary features in order to model similarity between items.
* The most interesting results are displayed in [4.3 SOM - MP votes](https://github.com/philipclaesson/ANNDA/blob/master/lab2/4.3%20SOM%20-%20MP%20votes.ipynb) where the voting patterns of members of the Swedish Parliament are used as features, allowing to model each member into a 2-dimensional political scale.
* In [4.2 SOM - Cyclic Tour](https://github.com/philipclaesson/ANNDA/blob/master/lab2/4.2%20SOM%20-%20Cyclic%20Tour%20-%20final.ipynb) a number of points in the 2 dimensional space are ordered by similarity (proximity) and the shortest path is estimated, serving as an estimation of the Travelling Salesman Problem.
* In [4.1](https://github.com/philipclaesson/ANNDA/blob/master/lab2/4.1%20SOM.ipynb) a more basic example regarding a set of animals each with a set of binary features are ordered by similarity.