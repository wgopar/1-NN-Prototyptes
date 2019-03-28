# 1-NN-Prototyptes

In a Nearest Neighbor classifier it is necessary to compare pair-wise distances between test points and those points in the training set to assign labels. In order to reduce computation, we can use a subset of data corresponding to each label (e.g prototypes) and only compute the pair-wise distances to those points. How do we choose the best prototypes of each class? 

I experiment with randomly selecting subsets of each class to selecting subsets of data where it is most dense. See notebook for more details. 

#### Data 

Obtained from: https://pypi.org/project/python-mnist/
