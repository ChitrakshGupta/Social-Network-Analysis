# Social Network Analysis in Python (Email Dataset)

## Introduction
Welcome to the Social Network Analysis in Python repository! Networks have become an integral part of our daily lives, and this project aims to help you visualize and understand social networks using Python's NetworkX library.

## Dataset Information
The dataset used in this project is the Enron email network dataset from Stanford SNAP. It contains email communication data from Enron employees, which can be used to analyze the network of interactions within the company.

## Methods for Analysis
1. **Betweenness Centrality**: Measures the number of shortest paths that pass through a node, indicating its importance in connecting different parts of the network.
2. **Degree Centrality**: Measures the number of connections a node has, highlighting nodes with high influence or connectivity.
3. **Closeness Centrality**: Measures how close a node is to all other nodes in the network, identifying nodes with efficient communication paths.
4. **Eigenvector Centrality**: Measures the influence of a node based on the influence of its neighbors, identifying nodes with connections to other influential nodes.
5. **Degree Distribution**: Describes the distribution of node degrees in the network, providing insights into the network's structure and connectivity patterns.

## Usage
1. Install the required libraries:
   ```bash
   pip install networkx matplotlib
