- [Overview](#overview)
- [String Skill](#string-skill)
  - [Regex](#regex)
    - [JavaScript](#javascript)
  - [Repeat String Concatenation](#repeat-string-concatenation)


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