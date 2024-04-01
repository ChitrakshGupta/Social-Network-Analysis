# Social Network Analysis

## Definition and Basics
- **Social Network**: A social network is a representation of relationships between individuals or entities, where nodes represent these entities, edges represent connections between them, and degree measures the number of connections each node has.

## Representation of Social Networks
- **Adjacency Matrix**: A matrix representation where rows and columns correspond to nodes, and entries indicate the presence or absence of edges.
- **Adjacency List**: A list representation where each node has a list of its neighbors.
- **Edge List**: A list of edges in the network.
![Image Description](https://drive.google.com/uc?id=14tZ6HvwIIWKSOAb0mBBbZLBhq17xxq7f)

### Complexities
- Adjacency Matrix: O(n^2) space complexity.
- Adjacency List: O(n + m) space complexity, where n is the number of nodes and m is the number of edges.
- Edge List: O(m) space complexity, where m is the number of edges.

## Comparison of Degree Calculation
- Compare the efficiency of degree calculation among the three representations.

## Three Pillars of Social Network Analysis
1. **Average Path Length**: The average shortest path length between all pairs of nodes in the network.
   - Formula: $APL = \frac{\sum_{i,j \in V} d(i, j)}{n(n-1)}$
2. **Clustering Coefficient**: Measures the degree to which nodes in a graph cluster together.
   - Formula: $CC = \frac{3 \times \text{Number of Triangles}}{\text{Number of Connected Triples}}$
3. **Degree Distribution**: Describes the distribution of node degrees in the network.

## Degree Distribution Types
- **Link Prediction**: Predicting future connections in a network based on existing connections.
- **Community Detection**: Identifying densely connected groups of nodes.
- **Information Diffusion**: Modeling the spread of information in a network.

### Models
1. **Linear Threshold Model (LT)**: Nodes adopt a behavior if a sufficient percentage of their neighbors already exhibit that behavior.
   - Formula: $p_i = \sum_{j=1}^{n} A_{ij}x_j \geq T_i$
2. **Independent Cascade Model (IC)**: Nodes have a probability of adopting a behavior from each of their neighbors.
   - Formula: $p_i = 1 - \prod_{j=1}^{n} (1 - A_{ij}x_j)$

## Social Influence Maximization
- Process of identifying the most influential nodes in a network to maximize the spread of information or behavior.

## Recommendation System
![Image Description](![Image Description](https://drive.google.com/file/d/1SK-BJ_WN_kvdAkH6GvTImYihkI_NUO7X/view?usp=sharing)

- Quantify node importance using centrality metrics:
  1. Degree Centrality
  2. Closeness Centrality
  3. Betweenness Centrality
  4. Eigenvector Centrality

## Contents of This Repository
- Program to find average path length
- Program to calculate degree distribution
- Calculation of clustering coefficient
- Influence calculation based on IC and LT models with seed sets
- Analysis of the Enron email network dataset from [Stanford SNAP](https://snap.stanford.edu/data/email-Enron.html)
# Social-Network-Analysis
