# Homework 1
## 1.In the following graphs, give the orders of vertices traversed by Breadth-First Search (BFS) and Depth-First Search (DFS) respectively. In addition, give the pre and post numbers of each vertex in each graph traversal. Break ties by alphabetical order, and begin your DFS and BFS searches from A.
Graph 1: BFS: A, B, C, D, E, F, G; DFS: A, B, E, C, F, D, G.<br>
Graph 2: BFS: A, C, D, G, F, E, B; DFS: A, C, F, D, E, G, B.<br>
Graph 3: BFS: A, B, E, G, C, D, F; DFS: A, B, C, D, F, E, G.<br>
## 2. There are n cities and m canals, where each canal connects two cities and has an associated integer w ∈ [0, W] representing its width. Suppose that you are at city a and would like to move to city b. A ship can travel on a canal if and only if its width is at most the width of the canal. You would like to move your belongings in as few trips as possible. Therefore, you would like to find a path from a to b that allows you to use the largest ship possible. What is the maximum width of a boat that can travel from city a to city b? 
### 1. Give an algorithm that finds both the maximum width and a valid path from city a to city b that allows the ship of that size to pass.
Correctness: 
### 2.Write down the runtime of your algorithm in n, m, W. 
Total runtime is O(mlogm+logW⋅(n+m).<br>
Justification: This takes O(m) time to iterate through the canals and O(mlog m) time to sort the unique widths. Each binary search step filters edges and performs graph traversal, which is efficient for sparse graphs where m is close to n. The binary search runs in O(log W) time, where W  is the maximum width.<br>
