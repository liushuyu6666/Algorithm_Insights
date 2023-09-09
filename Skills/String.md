- [Overview](#overview)
- [String Skill](#string-skill)
  - [Regex](#regex)
    - [JavaScript](#javascript)
  - [Repeat String Concatenation](#repeat-string-concatenation)
  - [String Mapping](#string-mapping)
    - [Create String Mapping](#create-string-mapping)
    - [Simplify String Mapping](#simplify-string-mapping)


# Overview
This page is dedicated to the skills of manipulating and evaluating strings.

# String Skill
## Regex
### JavaScript

**Code Examples**
```javascript
list = s.match(/(0+)|(1+)/g); // extract either one expression or another.
```

**Official Documents**
[Regex](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions)
    - [Assertions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Assertions)
    - [Character classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Character_classes): distinguish kinds of characters
    - [Groups and backreferences](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Groups_and_backreferences): group multiple patterns as a whole
    - [Quantifiers](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Regular_expressions/Quantifiers): numbers of characters or expressions to match.
    - [flags](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/RegExp#parameters).


## Repeat String Concatenation
The concept of a 'repeat string' typically involves two components: the "string" and the "pattern". The string should be constructed by the repeated concatenation of the pattern. For instance, the string "abcabc" is a repeat string with the pattern "abc".

Using "Repeat String Concatenation" can help determine whether a string has a repeating pattern or if two strings share the same repeating pattern.

1. [Check if a string has a repeating pattern](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Repeated_Substring_Pattern#repeat-string-concatenation)
2. [Check if two strings share the same repeating pattern](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/blob/master/Greatest_Common_Divisor_of_Strings/Readme.md)

## String Mapping
### Create String Mapping
If the mapping need to be built, we can employ two types of mappings:
1. Map two entities to each other, as exemplified by "egg" and "add":
   ```text
   map1         map2
   e -> a       a -> e
   g -> d       d -> g
   ```
2. Map both entities to a third entity:
   ```text
   map1         map2
   e -> 1       a -> 1
   g -> 2       d -> 2
   ```
### Simplify String Mapping
In some "Isomorphic/String Mapping" questions, the mapping is predefined. There are ways to utilize this mapping more efficiently.
[Simplify String Mapping](https://github.com/liushuyu6666/Algorithm_Leetcode_JavaScript/tree/master/Sentence_Similarity#simplify-string-mapping)