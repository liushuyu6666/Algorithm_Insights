- [Overview](#overview)
- [Sub-type of All Caveats](#sub-type-of-all-caveats)
  - [Redundant Conditional Checking](#redundant-conditional-checking)
  - [Max Integer Initialization](#max-integer-initialization)
    - [Examples](#examples)
  - [Connectivity missing](#connectivity-missing)
  - [Infinite dfs](#infinite-dfs)
  - [Father is not ancestor in Union Find](#father-is-not-ancestor-in-union-find)



# Overview

# Sub-type of All Caveats
## Redundant Conditional Checking
If the while loop has multiple parts, the condition needs to be redundantly checked within each part of the loop's body due to:
   1. **Sequential Execution**: Each part is executed within the loop sequentially.
   2. **Dynamic Variable Updates**: Since conditional variables will be updated within each part, it is necessary to reevaluate the condition before proceeding to the next part.
![Redundant Conditional Checking](static/Redundant_Conditional_Checking.png)

## Max Integer Initialization
We must exercise caution when initializing an element with the maximum integer value, as incrementing it later could result in an overflow and potentially lead to unexpected issues.

### Examples
- [01 Matrix](https://github.com/liushuyu6666/Leetcode_Java/tree/master/src/Zero_One_Matrix)


## Connectivity missing
In certain 'Connectivity Questions', [some nodes are missing from the connectivity relationships](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Number_of_Connected_Components_in_an_Undirected_Graph#connectivity-missing).

## Infinite dfs
One case of the infinite dfs problem is [here](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Number_of_Connected_Components_in_an_Undirected_Graph#infinite-dfs)

## Father is not ancestor in Union Find
Detail can be found [here](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/blob/master/Sentence_Similarity_II/Readme.md#father-is-not-ancestor-in-union-find).


