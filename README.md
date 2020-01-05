# kNN Algorithm

This README outlines the details of k-nearest neighbors algorithm in machine learning

## Prerequisites

You will need the following things properly installed on your computer.

* [python3.6](https://www.python.org/downloads/)
* numpy
* matplotlib 
* pandas
* dataset 

or you can use google colab notebook
* https://colab.research.google.com

## Explanation
The k-Nearest-Neighbors (kNN) method of classification is one of the simplest methods in machine learning,It simply calculates the distance of a new data point to all other training data points. The distance can be of any type e.g Euclidean or Manhattan etc. It then selects the K-nearest data points, where K can be any integer. Finally it assigns the data point to the class to which the majority of the K data points belong.

## steps
* Choose the number of K of neighbours.
* Take the L nearest neighbors of the new data point, according to the Euclidean distance.
* Among these K neighbours count the number of dat points in each category.
* Assign the new data point to the category where you counted the most neighbours.
