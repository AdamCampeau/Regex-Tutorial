# Regex Tutorial

Regular Expression

## Summary

Regex is a sequence of characters used for searching and editing strings.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

An anchor keeps a matched expression in a specific position in a strings, like an anchor.

Types:

(^)     Start of String
($)     End of String
(\b)    Word Boundary
(\B)    Non-Word Boundary

### Quantifiers

Specifies the amount a character appears.

Types:

(+)     Expression matched 1≥ time(s)
(?)     Expression matched 0≥ time(s)
({n})   Expression matched n time(s)
({n,})  Expression matched n≥ time(s)
({n,m}) Expression matched n - m range

### OR Operator

(|)     Logically provides OR option 

### Character Classes

([])    Matches at least 1 character in expression, can search for multiple

### Flags

Flags change the behaviour of an expression

Types:

(/g)    All instances of pattern is returned
(/m)    Anchors match start/end of string
(/i)    Matches text, case insensitive

### Grouping and Capturing

(())     Group and capture exressions togethor

### Bracket Expressions

([])    Searches expression through Character classes
(())    Capturing and grouping expressions
({})    Matches set amount of times

### Greedy and Lazy Match

GREEDY
Matches the pattern as much as possible, creating a bigger string.

LAZY 
Matches the pattern as little as possible, creating a smaller string.

### Boundaries

Matches words.

Types:

(\b)    Searches for word characters, alphanumerically.
(\B)    Searches for all characters.

### Back-references

(\1)    Matches text that was previously matched.

### Look-ahead and Look-behind

LOOK-AHEAD
(?=)    Sets what follows the current position.

LOOK-BEHIND
(?<=)   Sets what precedes the current position.

## Author

Adam Campeau
https://github.com/AdamCampeau

(2022-02-26)
