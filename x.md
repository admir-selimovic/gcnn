

# Distinguishing Characteristics of Graphs, Hypergraphs, Simplicial Complexes, and Cell Complexes

The distinguishing feature of graph neural networks is their capability to capture pairwise relations between entities in a graph, which makes them effective in solving various graph-based machine learning problems. Specifically, they can learn to aggregate and transform information from neighboring nodes in the graph to compute node representations that encode complex relational patterns. This allows them to incorporate arbitrary pairwise relational structures, such as edges between nodes, in their computations. By processing such relational structures, graph neural networks can extract meaningful features and patterns from the graph that can be leveraged for a variety of tasks, including node classification, link prediction, and graph classification. 
However, graphs alone have limitations in capturing multi-level interactions. As a result, the expressive power of such schemes is restricted, and they may not fully capture the richness of the data. 
Not all data can be expressed solely in terms of pairwise relationships and may not be supported on the nodes of a graph. To represent more complex structures in datasets, the use of graph models may not be sufficient. 
%For instance, social network interactions may involve larger groups of people beyond pairwise relationships. 
Hence, the need arises to extend graph-based models to capture higher-order interactions and more complex relational structures. 


For the comparison that follows, we need to introduce hypergraphs. A hypergraph is a generalization of a graph. It can be defined as a pair $(V, E)$, where $V$ is a set of vertices, and $E$ is a set of hyperedges. Each hyperedge $e \in E$ is a subset of $V$, meaning that it can contain any number of vertices from the vertex set. The vertices within a hyperedge are said to be incident to that hyperedge. Since we will not discuss hypergraphs beyond this section, we will not go further into elaborating them; for an in-depth introduction to hypergraphs, we defer the reader to \autocite{berge1984}.
