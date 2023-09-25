# Regex Tutorial

In this module I am describing what the characters mean in the following `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

## Summary

This regex `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/` is creating test for an input that matches an email. In this regex the email will match the entire string. 

## Table of Contents
<!-- use regexr to figure out what I will need or don't need using cheat cheat -->
- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes-and-bracket-expressions)
- [Grouping and Capturing](#grouping-and-capturing)


## Regex Components


### Anchors

`^` and `$` act as anchors in this regex. Specifically, the `^` acts as the start anchor of the string, and the `$` acts the end point of the string. 

### Quantifiers

The quantifiers in this regex are looking for the number of the given grouping that it follows. 
Here are the quantifiers in the regex:
 1. `([a-z0-9_\.-]+)` and the `+` is the acting quanifiter in this and indicates that there will be 1 or more of the preceeding strings described in the grouping. 
 2. `([\da-z\.-]+)` and the `+` is the acting quanifiter in this and indicates that there will be 1 or more of the preceeding strings described in the grouping. 
 3. `([a-z\.]{2,6})` and the `{2, 6}` is the acting quanifier in this grouping and it translates that there will be between 2 and 6 of the preceeding grouping. 

### Character Classes and Bracket Expressions
The character classes are described within the square brackets in the Regex, and they indicate what group of characters would match whats within the relative square braces.

1. `[a-z0-9_\.-]` the `a-z` means that any letter between a through z in the alphabet would be acceptable. `0-9` means that any number would be acceptable. `_\.-` means that any one of these three special symbols are acceptable to pass the test. 

2. 


### Grouping and Capturing
The grouping of the regex is idenitified by the paranthesis around the relative group. 

1. `([a-z0-9_\.-]+)` this the specified first grouping to capture. The first part is capturing the user name for the email. 

2. `([\da-z\.-]+)` this is the speceified second grouping to capture. The second part captures the domain of the email. 

3. `([a-z\.]{2,6})` this is the specified third grouping in the regex to capture. The third part captures the domain suffix. 


### Bracket Expressions



## Author

<!-- add my github profile -->
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
