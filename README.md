# Machine Learning in EDA  
This repository contains a brief description of the main areas of machine learning and neural networks applications for Electronic Design Automation(EDA).  
Nowadays the usage of ML for EDA is rapidly gaining popularity in the field of chip design. The three main approaches (*from my personal experience*) of 
ML algorithms application for design purposes are presented below.

  * Supervised Design Metrics Prediction
  * Unsupervised Design Optimization
  * Reinforcement Learning Optimization 

These approaches differ in the classes of algorithms used and in the result we want to get from them.
For example in Supervised Metrics Prediction we want to estimate the final crucial metricls of design without real implementation.
Accurate prediction algorithm at early design stages can essentially reduce time consumption, it minimize the time of 
further suboptimal physical implementations.  
In Unsupervised Design Optimization we want to have algorithm that helps us to improve our 
physical design flow and get better metrics as a result. Reinforcement Learning algorithms often uses to automize and speed up processes. 

In this field, a wide variety of machine learning algorithms are used for various tasks, but the most popular algorithm 
is [Graph Neural Networks(GNNs)](https://distill.pub/2021/gnn-intro/). The reason of GNN's popularity is quite simple, since [netlist](https://en.wikipedia.org/wiki/Netlist) 
represented as a graph, it is convenient to use graph machine learning methods to work with it. GNNs extract features from netlist and form embeddings to work with. 

## Some articles 

  * Supervised Design Metrics Prediction
    1. [A Timing Engine Inspired Graph Neural Network Model for Pre-Routing Slack Prediction](https://dl.acm.org/doi/abs/10.1145/3489517.3530597)
    2. [Generalizable Cross-Graph Embedding for GNN-based Congestion Prediction](https://ieeexplore.ieee.org/abstract/document/9643446)
    3. [MAVIREC: ML-Aided Vectored IR-Drop Estimation and Classification](https://ieeexplore.ieee.org/abstract/document/9473914)
     
  * Unsupervised Design Optimization
    1. [VLSI Placement Optimization using Graph Neural Networks](https://mlforsystems.org/assets/papers/neurips2020/vlsi_placement_lu_2020.pdf)
    2. [Placement Optimization via PPA-Directed Graph Clustering](https://dl.acm.org/doi/abs/10.1145/3551901.3556482)
     
  * Reinforcement Learning Optimization
    1. [A graph placement methodology for fast chip design](https://www.nature.com/articles/s41586-021-03544-w)
    2. [GCN-RL Circuit Designer: Transferable Transistor Sizing with Graph Neural Networks and Reinforcement Learning](https://ieeexplore.ieee.org/abstract/document/9218757 )
