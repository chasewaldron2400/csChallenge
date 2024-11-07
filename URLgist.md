# URL Regex

`/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/`

## Summary

This regular expression is designed to accurately match and validate URLs.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors

 - ^ Asserts position at the start of the string.
 - $ Asserts position at the end of the string.

### Quantifiers

- * Matches zero or more occurrences of the preceding character or group.
- + Matches one or more occurrences of the preceding character or group.
- ? Marks the preceding character or group as optional.

### Grouping Constructs

- () Groups parts of the expression together for capturing quantifiers.

### Bracket Expressions

- [] Specifies a set of characters to match any character within the brackets.

### Character Classes

- \d Matches any digit (0-9).
- \w Matches any word character.
- [a-z] Matches any lowercase character.

### The OR Operator

- |  Represents an OR condition between parts of the regex.

### Flags

- g Global search matches all occurances.
- i Case insensitive search.
- m allows ^ and $ to match the start and end of each line. 

### Character Escapes

- \. Matches a . because the period is a special character in regex.
- \/\/ Matches // by escaping a foward slash.

## Author

This document was created by Chase Waldron 11/4/2024
https://github.com/chasewaldron2400