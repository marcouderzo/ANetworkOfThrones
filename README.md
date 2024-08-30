# A Network Of Thrones
<h3> Shedding Light on Game of Thrones through Character Interaction Networks </h3>

**Author:** Marco Uderzo

Game of Thrones is a popular fantasy drama TV series created by David Benioff and D.B. Weiss for HBO, adapted from George R.R. Martin's A Song of Ice and Fire novels. This project aims at analyzing the relationships between characters to find the most influential ones and understand the different political alliances, power dynamics and houses, as well as the main plot lines that shape the story. This analysis will offer insights into the complex social structure of Westeros and the strategies behind the quest for the Iron Throne.

## Materials and Methods

### Dataset

GitHub Repository: [Character Interaction Networks for the HBO Series "Game of Thrones"](https://github.com/mathbeveridge/gameofthrones)

Pairs of characters are connected by (undirected) edges weighted by the number of interactions. 

There are five interaction types. Character A and Character B are connected whenever:

- Character A speaks directly after Character B
- Character A speaks about Character B
- Character C speaks about Character A and Character B
- Character A and Character B are mentioned in the same stage direction
- Character A and Character B appear in a scene together

### Methods

- Metrics: Density, Small-World Network, Connected Graph, Diameter, Shortest Paths, Average Shortest Paths, Degree, Average Degree Distribution, Bridges.
- Centrality Measures: Betweenness, Closeness, Eigenvector, Harmonic, Degree, Weighted Degree, PageRank.
- Homophily Analysis: Assortativity Coefficient, Jaccard Similarity.
- Triangles Analysis: Total Number of Triangles, Frequency of Triangles, Average Clustering Coefficient, Global Clustering Coefficient (Triadic Closure).
- Community Detection: Infomap, Girvan-Newman, Louvain, Greedy Modularity Maximization, Spectral Clustering.
- Robustness: Random Nodes Removal, Centrality-Based Removal
- Link Prediction: Between existing nodes and between new nodes
- Temporal Evolution: Analysis of cumulative sum of node degree as a signal d<sub>i</sub>(t), from which death of characters and main events can be inferred.
