# CS205 2017 Spring Final Project 

Group Members (in alphabetical order): <br /> 
Jiahua Guo  <br />
Jiachen Song  <br />
Xinyuan Wang  <br />
Jiawei Zhuang  <br />

### Parallel software solution
We choose MPI + OpenMP/OpenACC/CUDA as our heterogenous computing environment. 

### Data science problem
Many huge data sets are now publicly available. There are several ways to turn those large amounts of data into useful knowledge. 
Here we focus on exploratory data analysis, or unsupervised machine learning, which means finding structural information without prior knowledge.

Among all the unsupervised learning methods, k-means is a commonly used algorithm, which partitions observations into k clusters in which each 
observation belongs to the cluster with the nearest mean. Finding the minimum of a k-means cost function is a NP-hard problem when the dimension 
d>1 and the number of clusters k>1. Scientists came up with several heuristic methods to find the local minimum, but the process is still highly 
computationally-intensive, especially with huge data sets. We want to implement a parallel version of a k-means heuristic method on a cluster of machines, 
to significantly speed up the computing time of the clustering process, without any reduction on the accuracy rate of the clustering model.


### Some data set options 
(Preliminary plan. Might change in the future.)

Hubway system data: <br />
https://www.thehubway.com/system-data

Airbnb data: <br />
http://data.beta.nyc/dataset/inside-airbnb-data

