- [Overview](#overview)
- [Sub-type of String Question](#sub-type-of-string-question)
  - [Characters Occurrences](#characters-occurrences)
  - [Character mapping](#character-mapping)
  - [Elements grouping](#elements-grouping)
    - [Categories](#categories)
  - [Parentheses Problem](#parentheses-problem)
    - [Categories](#categories-1)


# Overview
This page is dedicated to the manipulation and evaluation of strings, encompassing tasks such as inserting substrings into existing strings, shortening strings, extracting specific features from strings, and comparing multiple strings.

# Sub-type of String Question
## Characters Occurrences
This type of question only concerns the occurrence of letters, irrespective of the position of each letter. For instance, consider the count of occurrences of the letter 'p' in the word 'pattern'.

## Character mapping
This type of question focuses on both the occurrences of letters and their positions. For example, are 'paper' and 'title' isomorphic?

## Elements grouping
This problem intersects the concepts of strings and arrays, especially if characters in a string are viewed as elements of an array. Hence, the use of the term "elements" in this context.

Elements can be classified into two or more types. Within each type, all elements are considered equivalent.

### Categories
1. **Consecutive Element Counting**: Count the lengths of consecutive elements of the same type and perform additional operations based on these counts. One approach is to use a `stack` to store same type elements.
   * String/Array Creation Based on Count:
     * [Compress String LCCI](https://leetcode.cn/problems/compress-string-lcci/)
     * [Design Compressed String Iterator](https://leetcode.cn/problems/design-compressed-string-iterator/)
   * String/Array Splitting: **The solution approach can vary and more examples are required for a comprehensive understanding**
     * [Count Binary Substrings](https://leetcode.cn/problems/count-binary-substrings/)
     * [Split a String in Balanced Strings](https://leetcode.cn/problems/split-a-string-in-balanced-strings/): This is akin to a "parenthesis problem".
     * [Maximum Score After Splitting a String](https://leetcode.cn/problems/maximum-score-after-splitting-a-string/): This problem can also be approached as a "find the extremum" question, making dynamic programming a potential solution.
2. **Element Position Consideration**: Consider the position of varying element types and rearrange the order of the original array. Further examples are needed to understand fully.
   * [Reformat The String](https://leetcode.cn/problems/reformat-the-string/)
3. **Element Flipping**: Some problems might require flipping elements, which can also relate to matrix flipping. **More examples are needed to delve deeper**.
   * [Minimum Moves to Convert String](https://leetcode.cn/problems/minimum-moves-to-convert-string/)
   * [Minimum Changes To Make Alternating Binary String](https://leetcode.cn/problems/minimum-changes-to-make-alternating-binary-string/)

## Parentheses Problem
This problem combines the concepts of strings and arrays. Specifically, characters in a string can be thought of as elements of an array, which is why we use the term "elements" in this context.

In this problem, every element type has a corresponding paired type.

### Categories
1. Two paired elements can be offset against each other. A `stack` can be utilized to store these elements. When a new element is added to the stack, check if it can be paired with the topmost element (peek). If they can be paired, remove both elements from the stack.
   * [Split a String in Balanced Strings](https://leetcode.cn/problems/split-a-string-in-balanced-strings/)
   * [Robot Return to Origin](https://leetcode.cn/problems/robot-return-to-origin/)
   * [Remove All Adjacent Duplicates In String](https://leetcode.cn/problems/remove-all-adjacent-duplicates-in-string/)
   * [Valid Parentheses](https://leetcode.cn/problems/valid-parentheses/)

