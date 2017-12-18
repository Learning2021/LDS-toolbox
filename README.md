## LDS-toolbox: a matlab toolbox for linear dynamical systems (LDSs) modeling

#### Authors: [Wenbing Huang](https://sites.google.com/site/wenbinghuangshomepage/)

### Overview

Linear Dynamical Systems (LDSs) are fundamental tools for modeling spatiotemporal data in various disciplines. 
Though rich in modeling, analyzing LDSs is not free of difficulty, mainly because LDSs do not comply with Euclidean geometry
and hence conventional learning techniques can not be applied directly. Specifically, LDSs apply parametric equations to model
the spatio-temporal data. The optimal system parameters (i.e. the system tuple (A,C)) learned from the input are employed as
the descriptor of each spatio-temporal sequence. 

This directory contains code necessary to run the GraphSage algorithm.
GraphSage can be viewed as a stochastic generalization of graph convolutions, and it is especially useful for massive, dynamic graphs that contain rich feature information.
See our [paper](https://arxiv.org/pdf/1706.02216.pdf) for details on the algorithm.


If you make use of this code or the GraphSage algorithm in your work, please cite the following paper:

     @inproceedings{hamilton2017inductive,
	     author = {Hamilton, William L. and Ying, Rex and Leskovec, Jure},
	     title = {Inductive Representation Learning on Large Graphs},
	     booktitle = {NIPS},
	     year = {2017}
	   }

### Requirements


### Running the code



#### Input format

