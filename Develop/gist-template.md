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
Also known as Alternation Operators. It tells the regex engine to match either everything to the left of the vertical bar, or everything to the right of the vertical bar. If you want to limit the reach of the alternation, you need to use parentheses for grouping. It is typically used with Boolean.

These are some examples of OR Operators

(some truthy expression) || expr
expr1 || expr2

### Character Classes
Also known as character set, you can tell the regex engine to match only one out of several characters

These are some examples of Character Classes

`\d` - any single digit 0-9
`\w` - a word character
`\s` - spaces, tabs \t, new lines \n and a few other rare characters such as \v, \f, \r.

`\D` - Any character except \d
`\W` - Anything but \w
`\S` - Any character except \s

`.` - Any character if with the regexp 's' flag, otherwise any except a newline \n.
### Flags
Regex have six optional flags that allow for functionality like global and case insensitive searching. These flags can be used separately or together in any order, and are included as part of the regular expression.

These are some examples of flags.
`d` - Generates indices for substring matches.
`g` - Global search.
`i` - Case-insensitive search
`m` - multi-line search
`s` - Allows . to match newline characters.
`u` - "unicode"; treat a pattern as a sequence of unicode code points.
`y` - Perform a "sticky" search that matches starting at the current position in the target string.
### Grouping and Capturing

### Bracket Expressions

### Greedy and Lazy Match

### Boundaries

### Back-references

### Look-ahead and Look-behind

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
