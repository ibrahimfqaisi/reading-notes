# Graphs Overview

1. Introduction
   This document provides an overview of graphs as a data structure and covers various concepts and terminology associated with them. Graphs are collections of vertices (nodes) connected by edges, which can be used to model relationships between entities. The key points discussed include:

2. Basic Concepts

   1. Vertex: A data object with optional adjacent vertices.
   2. Edge: Connection between two nodes.
   3. Neighbor: Adjacent nodes connected by an edge.
   4. Degree: Number of edges connected to a vertex.

3. Types of Graphs

   1. Undirected Graph: Bidirectional edges, no specific direction.
   2. Directed Graph (Digraph): Edges have specific directions.
   3. Complete Graph: All nodes are connected to each other.
   4. Connected Graph: All nodes have at least one edge.
   5. Disconnected Graph: Some nodes lack edges.

4. Acyclic vs. Cyclic Graphs

   1. Acyclic Graph: No cycles, often represented as a Directed Acyclic Graph (DAG).
   2. Cyclic Graph: Contains cycles or loops.

5. Graph Representation

   1. Adjacency Matrix: 2D array indicating edges between vertices.
   2. Adjacency List: Collection of linked lists or arrays indicating connected vertices.
   3. Weighted Graphs: Edges have weights assigned to them.

6. Graph Traversals

   1. Breadth-First Traversal: Visits nodes level by level.
   2. Depth-First Traversal: Uses a stack to explore subtrees.

7. Real-World Applications

   1. GPS and Mapping: Navigational routes.
   2. Social Networks: Connections between users.
   3. Airline Traffic: Flight routes.
   4. Recommendations: Product suggestions, as seen on Netflix.

The document provides detailed explanations, visuals, and algorithms for both breadth-first and depth-first traversals. It emphasizes the importance of marking visited nodes to prevent infinite loops in cyclic graphs. The concepts of adjacency matrices and adjacency lists are covered for graph representation, including weighted graphs where edges have associated weights.

Overall, the document serves as an introductory guide to understanding graphs, their types, representations, traversals, and practical applications in various domains.
