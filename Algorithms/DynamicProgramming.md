- [dynamic programming](#dynamic-programming)


# dynamic programming
The algorithm comprises two core elements:
1. **Initial State**: Initialization values, like edge grids of a matrix or start indices.
2. **Transition Equation**: The rule or constraint governing the derivation of current states from previous states:
$$state[x] = f(state[x - 1])$$

There are some dynamic programming questions:
1. [Minimum Skips to Arrive at Meeting On Time](https://leetcode.cn/problems/minimum-skips-to-arrive-at-meeting-on-time/)

An intriguing thing is that the result of multiple dynamic programming methods can be combine to get the final result. [01 matrix](https://github.com/liushuyu6666/Leetcode_Java/tree/master/src/Zero_One_Matrix)