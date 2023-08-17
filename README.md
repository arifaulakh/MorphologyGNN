# MorphologyGNN

This repository contains code for the MorphologyGNN project. The MorphologyGNN project aims to use Graph Neural Networks (specifically Graph Convolutional networks)
to better classify neuron morphology data. This approach is motivated by current research to use Convolutional Neural Networks (CNNs) to classify this type of data, along with the 
use of more traditional machine learning methods such as Random Forest Classifiers (RFC).

This repository contains code that converts .SWC files into PyTorch Geometric objects (using NetworkX and MorphoPy packages) that can be fed into a Graph Convolutional Network written with PyTorch.

For future steps, we aim to create baselines by training RFCs on graph attributes of the morphology data for both the Gouwens and Scala datasets. Furthermore, we also hope to use transfer learning approaches as another method.