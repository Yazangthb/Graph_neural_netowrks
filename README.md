# Graph Analysis and Machine Learning on Graphs

This repository contains a series of hands-on labs focusing on graph theory, machine learning methods, and deep learning techniques for graph analysis. The labs explore traditional methods, node embeddings, and Graph Neural Networks (GNNs) using various graph-related algorithms. Each notebook is designed to help users understand and implement graph-based models and techniques.

## Notebooks

### 01. Introduction to Graphs
- Introduction to the `networkx` library in Python.
- Explanation of graphs, nodes, edges, and their components.
- Creating, manipulating, and analyzing graphs.
- Estimating graph connectivity and exploring graph types.

### 02. Traditional Methods for ML on Graphs
- Exploration of graph features like node degree and centrality measures (degree, closeness, betweenness).
- Overview of graph kernels for learning from graphs by transforming them into vectors for machine learning algorithms.

### 03. Node Embeddings
- Introduction to node embeddings and their applications in clustering, classification, and link prediction.
- Exploration of random walks, DeepWalk, and node2vec for generating node embeddings.
- Techniques to embed entire graphs using methods like DeepWalk, node2vec, and LINE.

### 04. Link Analysis: PageRank
- Understanding link analysis and the PageRank algorithm.
- Application of PageRank for identifying influential nodes and predicting link formation in a graph.

### 05. Label Propagation for Node Classification
- Introduction to the label propagation algorithm for node classification.
- Implementation of label propagation using neighbors’ labels to classify nodes efficiently.

### 06. Graph Neural Networks (GNNs)
- Introduction to Graph Neural Networks (GCNs) for node classification tasks.
- Exploration of the Cora citation dataset and implementation of GCN models for node classification.
- Training and evaluating GCN models, along with visualizing the training results.

### 07. Understanding Graph Embeddings with GraphSAGE
- Exploring the limitations of traditional graph embeddings.
- Understanding the GraphSAGE framework, focusing on neighborhood sampling, aggregation, and pooling techniques.
- Building and applying a GraphSAGE model.

### 08. Graph Isomorphism Network (GIN)
- Implementation of a basic GIN layer using PyTorch.
- Comparison of GIN with GCN on a graph classification dataset.
- Visualizing graph embeddings in 2D and 3D.
- Exploring advanced GIN topics like mini-batching and ensemble learning.

