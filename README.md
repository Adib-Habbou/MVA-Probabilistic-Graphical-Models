# Review of a Mixture Model for Random Graphs

Authors: Adib Habbou and Teddy Alexandre

## Introduction
This repository contains an exploration and review of mixture models for graphs and clustering. It delves into enhancing graph modeling by incorporating clustering structures, addressing limitations in traditional models, and providing a more realistic representation of complex real-world graphs.

## Content Overview
- **Erdos-Rényi Model**: Overview of the classical model for random graphs.
- **Mixture Model for Degrees**: Extension of Erdos-Rényi to incorporate clusters and hidden variables for more realistic degree distributions.
- **Erdos-Rényi Mixture for Graphs (ERMG)**: Introduction of a new model that considers cluster distributions and probabilities for inter-cluster connections.
- **EM Algorithm**: Description and implementation details of the Expectation-Maximization algorithm for parameter estimation.
- **Experiments**: Comparison of graph properties between Erdos-Rényi, Mixture Model for Degrees, and ERMG.
- **Limitations**: Discussion on limitations observed in ERMG graph generation and the EM algorithm's instability.
- **Conclusion**: Summary of findings and the importance of context-driven choices in graph modeling.
- **Contributions**: Details on the individual contributions of Adib and Teddy to the project.

## Experiments and Results
The repository includes implementations of the models discussed in the article, along with experiments comparing their performance in generating random graphs. The results are showcased through metrics such as average degree, path length, graph density, efficiency, clustering coefficient, and betweenness centrality.

## Issues Encountered
Challenges faced in implementing the Expectation-Maximization algorithm for ERMG are highlighted, emphasizing the instability and convergence issues experienced during experiments.

## Conclusion and Contributions
The review emphasizes the significance of ERMG in capturing structured connectivity in graphs. However, it acknowledges limitations and challenges in implementing the EM algorithm, paving the way for further refinement in graph modeling techniques.

### Appendix
The repository includes visual representations of generated graphs, illustrating Erdos-Rényi, Mixture Model for Degrees, and Erdos-Rényi Mixture for Graphs with different parameters.
