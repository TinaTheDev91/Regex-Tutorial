# HEX Code Regex Tutorial

* Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

To start, a Regex or Regular Expression is a series of different characters used to create a search pattern in code. When using these expressions, you are able to find text based on your desired pattern/format as well as manipulate the acquired text to suit your goal. These expressions are commonly used to determine if a user's new password meets a website's requirements or if a user's email is valid. As you dive further into this tutorial, you'll learn how a HEX code Regex is used and structured.

## Summary

A HEX code Regular Expression allows users to validate HEX (or Hexadecimal) color codes. These codes are often used spaces such as web development and design (ie, illustration and graphic design). When we see the code indicated among platforms, it is typically denoted with a '#' symbol, followed by a series of 6 characters which are a combination of both numbers and letters. The HEX Code Regex is as follows:

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

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
Regex use use the anchors `^` and `$` for the HEX Regex, it contains both.

`^` is used to indicate the beginning of a regex pattern, with the HEX Regex, the beginning of that pattern would be a `#`. When using this symbol (`^`), you are indicating that you want that particular pattern to be an exact match.

The second anchor used in this regex is the `$`. This particular symbol is used to dictate the end of your desired string. When adding a `$`, you are saying that the characters leading up to it are included at the end of your string.

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
