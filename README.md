# Discover_America
Here is a repository where I will share some of the tutorials we go over throughout the semester! 

### Tutorial 1:
Introduction to basic Scanpy functions: clustering, dimensionality reduction, data visualization, preprocessing, etc. Introduces the formulation of some fundamental ML techniques for gene expression data analysis including PCA and KMeans clustering. Also illustrates the poor performance of naively applying these methods to spatially resolved data.

### Tutorial 2:
Presents a more thorough motivation behind properly accounting for spatial relations in ST data. We introduce Moran's I, a measure of spatial autocorrelation between genes distributed among our spots / cells. We also introduce how this spatial autocorrelation structure can be used to weight our PCA dimensionality reduction for better clustering performance. 

### Tutorial 3:
Most state-of-the-art approaches to spatial clustering in ST data rely on some form of Graph Neural Network (GNN). This tutorial introduces the basic ANN / autoencoder framework as well as explaining how neural networks are trained to learn the structure of data via gradient descent and back propagation. 

### Tutorial 4
Given an autoencoder model, how can we now incorporate the spatial relations of the data? Ideally we would like to generate low dimensional gene expression representations that consider both the spatial structure as well as a spots gene expression levels. This motivates Graph Message Passing- the central feature of GNN models. Message passing refers to the information exchange and aggregation between spatially neighboring spots on our tissue during dimensionality reduction. Specifcally, we will introduce a basic Graph Convolution Network for ST data. 

### Tutorial 5
In this tutorial we will introduce Graph Attention mechanisms- a slightly more sophisticated graph message passing technique than GCNs and the backbone of the STAGATE method. 

### Tutorial 6
Topological PCA enables cell embeddings based on multi-scale correlations among cell gene expression profiles. When paired with a consensus clustering based approach to incorporate all of the scales of cell similarity connectivity, this is a powerful tool for scRNAseq cell type identification. 

### Tutorial 7
MCIST pairs the power of a spatially resolved graph deep learning method with the topological PCA modeling of multi-scale cell-cell expression similarities (or, in a sense, cell interactions). We can combine tPCA with STAGATE to deliver state-of-the-art spatial domain detection. 

I think past this point we can just focus on reproducing the results needed for our end of semester presentation
