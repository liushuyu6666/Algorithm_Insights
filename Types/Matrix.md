# Flip the Matrix
Each matrix element typically comprises two phases, and the task permits selective flipping of elements between phases, subject to specified constraints or rules, to achieve the desired outcome.

When given the ability to flip grids based on a specific rule, the visual effect resembles a grid's movement. Rather than focusing solely on flipping, consider planning a path to move the grid according to the desired transformation. Like this question [1975. maximum matrix sum](https://github.com/liushuyu6666/Leetcode_Java/tree/master/src/Maximum_Matrix_Sum)

# Rotate the Matrix
To perform a complete matrix rotation, systematically peel the matrix layer by layer, starting from the outermost and progressing towards the innermost layer. Subsequently, divide each layer into four quadrants for ease of manipulation. Finally, rotate each grid within the quadrants to achieve the desired rotation.
![rotate matrix](static/rotate_matrix.png)