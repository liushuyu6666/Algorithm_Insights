- [Overview](#overview)
- [Sub-type of Graph Question](#sub-type-of-graph-question)
  - [Connectivity Question](#connectivity-question)
    - [Categories](#categories)


# Overview
Questions of this nature pertain to the graph data structure, with trees being a specific type of graph.

# Sub-type of Graph Question
## Connectivity Question
These questions assesses the connectivity between two nodes, with questions stemming from the overall node connectivity. The underlying data structures can be either trees or graphs.

To solve the question, there are multiple approaches:
1. [Adjacency List](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Algorithms/Graph.md#adjacency-list)
2. [Union-Find](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Algorithms/Graph.md#union-find)

### Categories
1. **Tree-like Structure**: In this structure, each node has a singular direct parent (possibly itself) and can have multiple direct children.
   * [Kill Process](https://leetcode.cn/problems/kill-process/)
2. **Undirected Graph**: Within this structure, each node connects to one or more parent nodes and one or more child nodes.
   * [Number of Provinces](https://leetcode.cn/problems/number-of-provinces/)
   * [Number of Connected Components in an Undirected Graph](https://leetcode.cn/problems/number-of-connected-components-in-an-undirected-graph/)
   * [Sentence Similarity II](https://leetcode.cn/problems/sentence-similarity-ii/)