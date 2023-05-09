# Kruskal-Algorithm

Kruskal's algorithm is a greedy algorithm used to find the minimum spanning tree of a connected undirected graph. It operates by first sorting the edges of the graph in non-decreasing order of their weights. The algorithm then proceeds to add the edges one by one, from smallest to largest, to the resulting minimum spanning tree, while avoiding the creation of cycles. 

This process continues until all the vertices of the graph are included in the minimum spanning tree, or until the desired number of edges is reached. Kruskal's algorithm can be implemented using a Union-Find data structure to keep track of the vertices and detect cycles.

The time complexity of Kruskal's algorithm is O(E log E) or O(E log V), where E is the number of edges and V is the number of vertices in the graph. This makes it an efficient algorithm for finding the minimum spanning tree of large graphs.

Kruskal's algorithm has many practical applications, such as in network design, transportation planning, and image segmentation. Its simplicity and efficiency make it a popular algorithm.

![download](https://github.com/jassercmk1/Kruskal_algorithm_/assets/120596258/507b646e-ed45-43aa-98a5-ee75aa93c948)
Minimum spanning tree: [('C', 'E', 1), ('A', 'B', 2), ('A', 'C', 3), ('A', 'D', 3), ('D', 'F', 7), ('F', 'G', 9)]
