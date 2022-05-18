# Regex unpacked



## Summary

Regex is short for a Regular Expression.  A Regex is a sequence of characters used to search through text in a  document or webpage for strings of characters that match their search criteria. A good example would be an email. A Regex is made up of components which are explained in the following tutorial.

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
are used to position the text
^ start/beginning
$ end
\b bounds the perimeter.

-An example of bounded text is \b\w{4}\b.  This ensures that only words of 4 letters in length are highlighted. 
-A regex snippet of ^\w+$  will highlight a word of one or more letters on a line by it self. 

### Quantifiers
determine the numbers involved. An example of a quantifier in use would be \w{5}. In this example the Regex is looking for 5 letters in sequence. If the aim is to find 5 letter words then this small regex snippet may not, on occasion, have the desired effect as words longer than five would have their first five letters highlighted. This is when bounded [Anchors](#anchors) are used.

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags
Flag include global which signifies match all.
### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
