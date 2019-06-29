# Search Algorithms - Jaisimha Manipatruni
Basic algorithms for single-shot grid-based 2D path finding.

Single-shot means that the algorithms are tailored to answering a single pathfinding query (as opposed to other pathfinders that are suited to solving sequences of alike queries, e.g. queries on the same map but with different start and goal locations).

Grid-based means that a (regular square) grid is an essential part of the input. We follow center-based assumption which implies that distinct agent's locations are tied to the centers of the traversable cells (not to the corners). 

Description
==========
This project contains implementations of the following algorithms:
- Breadth First Search
- Dijkstra's algorithm
- A*
- Theta*
- Jump Point Search (JPS)

