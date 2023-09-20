# ntua-social-network-analysis

Lab Assignments for the [Social Network Analysis](https://www.ece.ntua.gr/en/undergraduate/courses/3379) course, during the 9th semester of the School of Electrical and Computer Engineering at the National Technical University of Athens.

## Lab 01 - Complex Network Topologies

The first lab was about analyzing and studying complex network topologies. The [NetworkX](https://networkx.org/) library was heavily utilized in this and the following labs. 

This lab included the following topics:

- Construction and visualization of complex networks - REG, RG(ER), RGG, SF(BA), SW(WS)
- Network metrics - Clustering Coefficient, Average Path Length, Diameter, Radius
- Node Centrality metrics - Degree, Closeness, Betweenness, Katz Centrality and PageRank 
- Network connectivity and robustness
- Evolutionary network transformations
- Real networks

## Lab 02 - Community Detection

The second lab was about community detection in artificial and real complex network topologies. 

On the first part, we studied a few real networks, created a few artifical ones and visualized them all. We then calculated and plotted the Degree Distribution, the Clustering Coefficient Distribution and the Closeness Centrality Distribution for each one.

On the second part, we used the Newman-Girvan algorithm, the Spectral Clustering algorithm and the Modularity Maximization algorithm to detect communities in the networks. For each algorithm, we tried to maximize two metrics, modularity score and performance score. Finally, we visualized the communities that were detected for each network.

## Lab 03 - Link Prediction

The third lab was about link prediction.

We, first, created the graph we will use later to predict links. We, then, calculated the Jaccard Coefficient, the Preferential Attachment and the Resource Allocation metrics for the graph.

Using the above metrics and a Random Forest Classifier, we predicted links for the graph. Finally, we utilized embeddings based on the Node2Vec algorithm that uses Random Walks, to predict links.
