# Title (replace with your title)

What IS Regex?

## Summary

Regex, or regular expression, is a sequence of characters used for searching and editing strings.

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

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
