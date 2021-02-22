# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

The following regex is used to validate an email address.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)  
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
In the regex given, the main components are checking for specific characters and a required length.  a-z is indicating that the input can contain characters a through z.  0-9 is indicating that the input can contain numbers 0 though 9, and the following is a list of special characters that are also valid.
### Anchors
/^ is used to indicate the beginning of a regex and $\ is stating the end.
### Quantifiers
The + is used to validate length.  The + states that the input must contain one or more of the valid characters.  {2,6} is more specific, it is stating that the input must contain at least 2 of the valid characters and no more than 6.  

### Character Classes
Character classes are used to tell the regex to match only one of the indicated values.  The characters are placed between two square brackets.  []

### Flags
Flags are used to match patterns.  In this case we have valid characters, then the @ symbol, more valid characters, a period depicted by \. and finally letters a-z between 2 and 6 characters long.
### Grouping and Capturing
The provided regex is grouped between the starting /^ and ending $\/
### Bracket Expressions
The provided regex uses the bracket expression "\d".  This is short hand for 0-9.

## Author

My name is Aidan and I am currently in the process of completing a coding boot camp through UCLA extension.  The link to my github is: 