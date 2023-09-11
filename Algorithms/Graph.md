
# Overview

# Sub-type of Graph Algorithm
## Adjacency List
An adjacency list streamlines the tree or graph structure by only documenting node connectivity. Typically, we represent this list using a Map instead of a traditional list.

Consider the following guidelines when constructing an adjacency list:

1. Identify the Structure:
   * **Tree**: Each node should have only one direct parent. The adjacency list format for a tree is `{parentNode => [direct child nodes]}`. Note that there's no need to list leaf nodes as keys. [Kill Process](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Kill_Process) indicates this case.
    ```text
        1 => [2, 3, 4]; // node 2, 3, 4 only have one direct parent node
        2 => [5, 6]; // node 5, 6 only have one direct parent node
        3 => [7, 8]; // // node 7, 8 only have one direct parent node
        9 => 9
    ```
   * **Graph**: Each node can have multiple direct parents. For a graph, use the format {node => [connected nodes]}. Ensure every node is listed as a key. [Number of Connected Components in an Undirected Graph](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Number_of_Connected_Components_in_an_Undirected_Graph) indicates this case
    ```text
        1 => [2, 3, 4];
        2 => [1, 3, 4]; // node 3, 4 have two direct parent node
        3 => [1, 2];
        4 => [1, 2];
    ```
2. Adjacency List as an Intermediate Step:
   * The adjacency list primarily serves as an intermediary tool to simplify problem-solving.
   * Use a `visited` array to keep track of nodes already visited.
   * To derive the final solution, implement depth-first search (DFS) or breadth-first search (BFS) on the adjacency list.


There are some Caveats:
1. (Connectivity missing)[https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/blob/master/Number_of_Connected_Components_in_an_Undirected_Graph/Readme.md#connectivity-missing]
2. (Infinite dfs)[https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/blob/master/Number_of_Connected_Components_in_an_Undirected_Graph/Readme.md#infinite-dfs]


## Union Find
Union-Find is employed to address connectivity problems. 

Connectivity problems can be broadly classified into two categories: (Static Connectivity and Dynamic Connectivity)[https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/blob/master/Sentence_Similarity_II/Readme.md#union-find].

There is one Caveats:
1. (father is not ancestor in union find)[https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Caveats/Readme.md#father-is-not-ancestor-in-union-find]