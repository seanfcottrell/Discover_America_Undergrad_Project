# Discover_America
Here is a repository where I will share some of the tutorials we go over throughout the semester! 

### Tutorial 1:
Introduction to basic Scanpy functions: clustering, dimensionality reduction, data visualization, preprocessing, etc. Introduces the formulation of some fundamental ML techniques for gene expression data analysis including PCA and KMeans clustering. Also illustrates the poor performance of naively applying these methods to spatially resolved data.

### Tutorial 2:
Presents a more thorough motivation behind properly accounting for spatial relations in ST data. We introduce Moran's I, a measure of spatial autocorrelation between genes distributed among our spots / cells. We also introduce how this spatial autocorrelation structure can be used to weight our PCA dimensionality reduction for better clustering performance. 

### Tutorial 3:
Most state-of-the-art approaches to spatial clustering in ST data rely on some form of Graph Neural Network (GNN). This tutorial introduces the basic ANN / autoencoder framework as well as explaining how neural networks are trained to learn the structure of data via gradient descent and back propagation. 

### Tutorial 4
Given an autoencoder model, how can we now incorporate the spatial relations of the data? Ideally we would like to generate low dimensional gene expression representations that consider both the spatial structure as well as a spots gene expression levels. This motivates Graph Message Passing- the central feature of GNN models. Message passing refers to the information exchange and aggregation between spatially neighboring spots on our tissue during dimensionality reduction. 

### Tutorial 5
Graph Convolution Neural Networks... TBD

### Tutorial 6
Graph Attention mechanisms ... TBD

### Tutorial 7
Presentation of popular methods in ST data analysis that utilize these Graph Neural Network architectures: SpaGCN and STAGATE ... TBD

### Tutorial 8
TBD
