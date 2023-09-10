- [Overview](#overview)
- [Sub-type of Array Algorithm](#sub-type-of-array-algorithm)
  - [Two Pointers / Sliding Window](#two-pointers--sliding-window)
    - [Categories](#categories)
  - [Array Mapping](#array-mapping)
  - [Letters Array](#letters-array)


# Overview
This concerns algorithms and techniques within array data structures.

# Sub-type of Array Algorithm

## Two Pointers / Sliding Window
The sliding window technique consistently follows a specific pattern. Initially, two pointers, denoted as `l` (left inclusive) and `r` (right exclusive), are established. Additionally, a container is utilized to store elements within the window, which can take the form of a `Set`, `Map`, or a simple array. During each progression of the right pointer (`r++`), conditions are evaluated, prompting adjustments to the left pointer as necessary.

```javascript
let l = 0, r = 0;
while(r < arr.length) {
    const ele = arr[r]; // ele is the element which is going to load into the sliding window.
    // other algorithm
    /**
     * while( ... ) {
     *     // other algorithms about the left boundary
     *     l++
     * }
     *
    */
    r++;
}
```


### Categories
1. The window starts with both boundaries at position 0. The right boundary slides to the right until the requirement is no longer met. At that point, the left boundary starts to move right, releasing some characters to meet the requirement again. Once this is done, the right boundary resumes its movement to the right:
   * [Longest Substring Without Repeating Characters](https://leetcode.cn/problems/longest-substring-without-repeating-characters/)
2. The window's left boundary starts at position 0 and moves to the right until the requirement is satisfied. After that, the window expands as mentioned in the previous item:
   * [Count Vowel Substrings of a String](https://leetcode.cn/problems/count-vowel-substrings-of-a-string/)


## Array Mapping
![array mapping](static/array_mapping.png).

This algorithm is applicable in the following scenario:
1. To maintain element consistency.

## Letters Array
We can utilize an array with 26 elements to store the occurrences of a specific letter as it appears in a string. Similarly, an array can be employed to store the count of distinct elements.