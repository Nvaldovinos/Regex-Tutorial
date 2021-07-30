# Regex Tutorial 

This is a tutorial that explains how a specific regular expression, or regex, functions by breaking down each part of the expression and describing what it does.

## Summary

    Regular Expression (REGEX) is a sequence of characters that specifies a search pattern. Usual patterns are used by string-searching algorithms to find and replace operations on strings. `/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/` is used to match a url.

# Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

# Regex Components
 

### Anchors

Anchors are used to identify specific location in a string. 

- `^` Anchors a match to the begining of a line when you use it as the first character in an expression. 
- `$` Anchors a match to the end of a line when you use it as the last character in an expression.

### Quantifiers

A quantifier specifies how many instances of a character, group or character class must be in the input or a match to be found. 

- `* ? +` quantifier matches the preceding element zero or more times, These are all types of greedy quantifiers.
- `{n,n} {2,6}` quantifier matches the preceding element exactly n times, where n is any integer .

### Grouping Constructs

Grouping Contructors a delineate the subexpressions of a regular expression and capture the substring of an input string. 

### Bracket Expressions

Bracket expressions are a matching list expression or a non-matching list expression. They are a list of enclosed  `[]` that matches any single character in that list. Such as `[a-z\.]`.

### Character Classes

Character class defines a set of characters, that can occur in an input string for a match succeed. 
- `\d` matches any decimal digits 0-9 as well as the decimal digits of a number of other character sets.

### The OR Operator

The 

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
