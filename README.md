# project-3
Vertex
Represents a single vertex in the graph.
Stores a unique identifier and a map of neighboring vertices with their corresponding edge weights.
Provides methods to add neighbors and retrieve adjacency information.
WeightedGraph
Manages the entire graph structure.
Allows adding vertices and edges, and retrieving vertices and their adjacency lists.
Supports undirected graphs by adding edges bidirectionally.
Search
Defines the interface for search algorithms.
Includes methods like hasPathTo to check if a path exists to a destination and pathTo to return the path.
BreadthFirstSearch
Implements BFS to find the shortest path in terms of the number of edges.
Uses a queue to explore vertices level by level, ignoring edge weights.
DepthFirstSearch
Implements DFS to traverse the graph deeply.
Uses recursion to explore as far as possible along each branch, tracking visited vertices to avoid cycles.
DijkstraSearch
Implements Dijkstra's algorithm to find the shortest path based on edge weights.
Uses a priority queue to process vertices in order of increasing distance, dynamically updating distances to ensure the shortest path.
Main
Demonstrates the usage of the graph and search algorithms.
Creates a sample graph with vertices and edges, runs BFS and Dijkstra's algorithm, and prints the results.
