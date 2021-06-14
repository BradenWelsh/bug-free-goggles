# Regex Tutorial

This is a quick tutorial of what Regex looks like and how it works. This can easily be broken down into simple easy to understand parts.

## Summary

Regex is short for regular expression. It is a string of text that you can make to create search patterns that match, locate, and manage text. 
Here is an example of Regex - /[\w._%+-]+@[\w.-]+\.[a-zA-z]{3,8}/

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
Characters within the Regex within the regular expression that allow the user to match strings that begin with or ends with specific characters.

These are some examples of Anchors
`^` - Start of string or line
`$` - End of string or line.
### Quantifiers
Specify how many instances of a character, group, or character class must be present in the input for a match to be found.

These are some examples of Quantifiers
/X./; // matches any character
/X*/; // Matches zero or several repetitions of letter X, is short for {0,}
/X+-/; // matches one or more repetitions of letter X, is short for {1,}
/X?/; // finds no or exactly one letter X, is short for is short for {0,1}.
// d{3}; // matches three digits. {} describes the order of the preceding liberal
// d{1,4} ; // means d must occur at least once and at a maximum of four
### OR Operator

### Character Classes

### Flags

### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
