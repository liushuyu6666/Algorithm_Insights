# Overview


# Greedy Algorithm in ordered differences array
In this context, with an array `original` and an integer `x`, the objective is to maximize the number of selected elements while ensuring that the minimum absolute difference between any two chosen elements is equal to or greater than `x`.

For instance, consider the array `original = [1, 5, 13, 8, 2, 21]`. When `x = 3`, the algorithm aims to select elements such as `[1, 5, 8, 13, 21]`, where the absolute differences between any two selected elements are equal to or greater than 3. Similarly, when `x = 8`, the goal is to pick elements like `[1, 13, 21]`.

The solution involves sorting the original array to obtain `original = [1, 2, 5, 8, 13, 21]`, followed by deriving an ordered differences array, denoted as `diffs = [1, 3, 3, 5, 8]`. Subsequently, a greedy algorithm is applied to the `diffs` array, iteratively traversing it while accumulating the difference.

Two exemplar problems—[1552. Magnetic Force Between Two Balls](https://leetcode.com/problems/magnetic-force-between-two-balls/description/) and [2517. Maximum Tastiness of Candy Basket](https://leetcode.com/problems/maximum-tastiness-of-candy-basket/description/)—highlight specific use cases, providing detailed explanations and solutions.

It's crucial to note the distinction between the ordered differences array and the unordered differences array. The former requires the original array to be sorted, whereas the latter handles frequently increasing or decreasing elements within a specific range of the original array. An illustrative example can be observed in[2528. Maximize the Minimum Powered City](https://leetcode.com/problems/maximize-the-minimum-powered-city/description/)