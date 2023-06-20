# HEX Code Regex Tutorial

* Matching a Hex Value: `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

To start, a Regex or Regular Expression is a series of different characters used to create a search pattern in code. When using these expressions, you are able to find text based on your desired pattern/format as well as manipulate the acquired text to suit your goal. These expressions are commonly used to determine if a user's new password meets a website's requirements or if a user's email is valid. As you dive further into this tutorial, you'll learn how a HEX code Regex is used and structured.

## Summary

A HEX code Regular Expression allows users to validate HEX (or Hexadecimal) color codes. These codes are often used spaces such as web development and design (ie, illustration and graphic design). When we see the code indicated among platforms, it is typically denoted with a '#' symbol, followed by a series of 6 characters which are a combination of both numbers and letters. The HEX Code Regex is as follows:

`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)

## Regex Components

### Anchors

Regex use use the anchors `^` and `$` for the HEX Regex, it contains both.

`^` is used to indicate the beginning of a regex pattern, with the HEX Regex, the beginning of that pattern would be a `#`. When using this symbol (`^`), you are indicating that you want that particular pattern to be an exact match.

The second anchor used in this regex is the `$`. This particular symbol is used to dictate the end of your desired string. When adding a `$`, you are saying that the characters leading up to it must be included in your string.

### Quantifiers

This expression also consists of 3 quantifiers, which are use to set the limits of the desired expression. The `?` means that the following set (the bracket expression explained below) has to be matched zero or one time with the desired string; `{}` is used to limit the number of characters required for that set of the string, the numbers being 3 or 6.

### Bracket Expressions

This Regex contains 2 bracket expressions, the beginning of the expression is denoted by a `[` (of course). When this symbol is used, it means that the characters in that placement must fulfil the parameters defined with said brackets. The parameters defined mean the following:

`a-f0-9`: meaning that after the `#`, the string should consist of the number of characters noted within the `{}` (explained above), which are a combination of uppercase or lowercase letters ranging from `A - F` and numbers ranging from `0 - 9`.

### Character Classes

There are 2 character expressions defined in the Regex, those being, **A-F** (capital letters, A - F), **a-f** (lowercase letter, a - f) and **0-9** (numerical digits)

### The OR Operator

There is one OR operator `|` between 2 bracket expressions, telling the system that the expression can be satisfied with 6 characters consisting of upper and lowercase letters from `A - F` and numbers from `0 - 9` **OR** 3 characters consisting of upper and lowercase letters from `A - F` and numbers from `0 - 9`

## Author

Hi! I'm Tina Croxton, at the time of writing this, I am a student in Georgia Tech's FullStack Web Development Bootcamp. I am a Rutgers University graduate with a Bachelors in Mathematics. I am also a Graphic Designer for @SliceOfAnimeNW on IG, YouTube, TikTok and Twitter.

To see my developer work, please follow the link to my GitHub profile below:

https://github.com/TinaTheDev91
