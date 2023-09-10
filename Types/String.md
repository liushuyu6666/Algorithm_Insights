- [Overview](#overview)
- [Sub-type of String Question](#sub-type-of-string-question)
  - [Characters Occurrences](#characters-occurrences)
  - [Character mapping](#character-mapping)
  - [Elements grouping](#elements-grouping)
    - [Categories](#categories)
  - [Parentheses Problem](#parentheses-problem)
    - [Categories](#categories-1)
  - [Reverse String](#reverse-string)
    - [Categories](#categories-2)
  - [Repeat String](#repeat-string)
    - [Categories:](#categories-3)
  - [Palindrome](#palindrome)
    - [Categories](#categories-4)
  - [Consecutive Substring](#consecutive-substring)
    - [Categories](#categories-5)
  - [String Shift](#string-shift)
    - [Categories](#categories-6)
  - [Number and String](#number-and-string)
    - [Categories](#categories-7)
  - [Pattern Matching](#pattern-matching)
    - [Categories](#categories-8)
  - [Isomorphic / String Mapping](#isomorphic--string-mapping)
    - [Categories](#categories-9)


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
     * [Count Binary Substrings](https://leetcode.cn/problems/count-binary-substrings/).
     * [Split a String in Balanced Strings](https://leetcode.cn/problems/split-a-string-in-balanced-strings/): This is akin to a "parenthesis problem".
     * [Maximum Score After Splitting a String](https://leetcode.cn/problems/maximum-score-after-splitting-a-string/): This problem can also be approached as a "find the extremum" question, making dynamic programming a potential solution.
     * [Check if String Is Decomposable Into Value-Equal Substrings](https://leetcode.cn/problems/check-if-string-is-decomposable-into-value-equal-substrings/).
     * [Find the Longest Balanced Substring of a Binary String](https://leetcode.cn/problems/find-the-longest-balanced-substring-of-a-binary-string/), This is also a binary string.
2. **Element Position Consideration**: Consider the position of varying element types and rearrange the order of the original array. Further examples are needed to understand fully.
   * [Reformat The String](https://leetcode.cn/problems/reformat-the-string/)
3. **Element Flipping**: Some problems might require flipping elements, which can also relate to matrix flipping. **More examples are needed to delve deeper**.
   * [Minimum Moves to Convert String](https://leetcode.cn/problems/minimum-moves-to-convert-string/)
   * [Minimum Changes To Make Alternating Binary String](https://leetcode.cn/problems/minimum-changes-to-make-alternating-binary-string/)
   * [Flip Game](https://leetcode.cn/problems/flip-game/)

## Parentheses Problem
This problem combines the concepts of strings and arrays. Specifically, characters in a string can be thought of as elements of an array, which is why we use the term "elements" in this context.

In this problem, every element type has a corresponding paired type. When two paired elements meet, they will be offset. It's important to note that the issue with parentheses always pertains to consecutive paired elements. Thus, the problem can be extended: when `n` consecutive elements come into contact, one or more of them must be offset.

### Categories
1. Two paired elements can be offset against each other. A `stack` can be utilized to store these elements. When a new element is added to the stack, check if it can be paired with the topmost element (peek). If they can be paired, remove both elements from the stack.
   * [Split a String in Balanced Strings](https://leetcode.cn/problems/split-a-string-in-balanced-strings/)
   * [Robot Return to Origin](https://leetcode.cn/problems/robot-return-to-origin/)
   * [Remove All Adjacent Duplicates In String](https://leetcode.cn/problems/remove-all-adjacent-duplicates-in-string/)
   * [Valid Parentheses](https://leetcode.cn/problems/valid-parentheses/)
   * [Make The String Great](https://leetcode.cn/problems/make-the-string-great/)
   * [Minimum String Length After Removing Substrings](https://leetcode.cn/problems/minimum-string-length-after-removing-substrings/)
2. When `n` consecutive elements appear, offset one or more of them.
   * [Delete Characters to Make Fancy String](https://leetcode.cn/problems/delete-characters-to-make-fancy-string/)
   * [Largest 3-Same-Digit Number in String](https://leetcode.cn/problems/largest-3-same-digit-number-in-string/)


## Reverse String
This question requires you to reverse the entire string or a part of it. The built-in function you can use depends on the programming language you choose.

### Categories
1. Reverse the string.
   * [Reverse String](https://leetcode.cn/problems/reverse-string/)
   * [Reverse String II](https://leetcode.cn/problems/reverse-string-ii/)
   * [Reverse Vowels of a String](https://leetcode.cn/problems/reverse-vowels-of-a-string/)
   * [Reverse Words in a String III](https://leetcode.cn/problems/reverse-words-in-a-string-iii/)
2. Check if two strings are reversed versions of each other.
   * [Find Maximum Number of String Pairs](https://leetcode.cn/problems/find-maximum-number-of-string-pairs/)


## Repeat String

The concept of a 'repeat string' typically involves two components: the "string" and the "pattern". The string should be constructed by the repeated concatenation of the pattern. For instance, the string "abcabc" is a repeat string with the pattern "abc".

Here are some valuable skills that can help us address the question:
1. [Repeat String Concatenation](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Skills/String.md#repeat-string-concatenation)

### Categories:
1. Just need to check if a string contains repeat pattern:
   * [Repeated Substring Pattern](https://leetcode.cn/problems/repeated-substring-pattern/)
   * [Greatest Common Divisor of Strings](https://leetcode.cn/problems/greatest-common-divisor-of-strings/)
2. Need to build a repeat string:
   * [Repeat String](https://leetcode.cn/problems/repeat-string/)



## Palindrome
Another term related to palindrome is "symmetry." For instance, "aabbaa" is a palindrome string.

### Categories
1. Rearrange characters to form a palindrome. This type of question has an overlap with the category "character frequency", as both require counting the frequency of characters.
   * [Palindrome Permutation](https://leetcode.cn/problems/palindrome-permutation/)
   * [Longest Palindrome](https://leetcode.cn/problems/longest-palindrome/)
2. Verify if the string is a palindrome. We can use depth-first search or dynamic programming to perform this check.
   * [Valid Palindrome II](https://leetcode.cn/problems/valid-palindrome-ii/)
   * [Find First Palindromic String in the Array](https://leetcode.cn/problems/find-first-palindromic-string-in-the-array/)


## Consecutive Substring
The task is to find a consecutive substring within the given string, following the rules specified in the question. Use the sliding window technique to solve this type of problem.

### Categories
1. [Longest Substring Without Repeating Characters](https://leetcode.cn/problems/longest-substring-without-repeating-characters/)
2. [Count Vowel Substrings of a String](https://leetcode.cn/problems/count-vowel-substrings-of-a-string/)


## String Shift

String can be shifted to the right or to the left. but keep the consecutive order.

**More questions needed**

### Categories
1. [String Rotation LCCI](https://leetcode.cn/problems/string-rotation-lcci/)
2. [Perform String Shifts](https://leetcode.cn/problems/perform-string-shifts/)


## Number and String

This type of question involves converting numbers into strings or translating some or the entire string into a number.

### Categories
1. Nothing Special
   * https://leetcode.cn/problems/largest-odd-number-in-string/
   * https://leetcode.cn/problems/excel-sheet-column-number/
   * https://leetcode.cn/problems/excel-sheet-column-title/
   * https://leetcode.cn/problems/roman-to-integer/
   * https://leetcode.cn/problems/similar-rgb-color/
   * https://leetcode.cn/problems/strobogrammatic-number/
   * https://leetcode.cn/problems/valid-word-abbreviation/
   * https://leetcode.cn/problems/calculate-digit-sum-of-a-string/
   * https://leetcode.cn/problems/number-of-lines-to-write-string/
   * https://leetcode.cn/problems/sum-of-digits-of-string-after-convert/
   * https://leetcode.cn/problems/number-of-different-integers-in-a-string/
   * https://leetcode.cn/problems/decrypt-string-from-alphabet-to-integer-mapping/



## Pattern Matching

This type of question is straightforward. Here are some algorithms:
1. [KMP](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Algorithms/String.md#kmp)

### Categories
1. Find a pattern in a string:
   * [String Matching in an Array](https://leetcode.cn/problems/string-matching-in-an-array/)
   * [Index Pairs of a String](https://leetcode.cn/problems/index-pairs-of-a-string/)
   * [Count Prefixes of a Given String](https://leetcode.cn/problems/count-prefixes-of-a-given-string/)
   * [Number of Strings That Appear as Substrings in Word](https://leetcode.cn/problems/number-of-strings-that-appear-as-substrings-in-word/)

## Isomorphic / String Mapping

Isomorphism primarily deals with string mapping. In such problems, we consistently encounter two entities, which can either be strings or string arrays. The mapping can be categorized into:
1. Mapping a string to a character,
2. Mapping a string to another string,
3. Mapping a character to another character.


### Categories
1. The mapping is not pre-defined, we need to [create string mapping](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Skills/String.md#create-string-mapping)
   * [Word Pattern](https://leetcode.cn/problems/word-pattern/)
   * [Isomorphic Strings](https://leetcode.cn/problems/isomorphic-strings/)
2. The mapping is pre-defined, we need to [simplify string mapping](https://github.com/liushuyu6666/Algorithm_Insights/blob/master/Skills/String.md#simplify-string-mapping)
   * [Sentence Similarity](https://leetcode.cn/problems/sentence-similarity/)