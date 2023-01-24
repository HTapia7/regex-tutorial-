# Regular Expression - Matching an Email

I will be creating a short tutorial using regex to match emails. 

## Summary

I will be breaking down the regex rxpress into its several components. I will go in depth on each section of the express. The expression that I will be explaining in the tutorial is: 

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)

## Regex Components

### Anchors

The two anchors being used in this expression are Caret(^) and Dollar Sign($) located at the beginning and end of the expression. The Caret signifies the beginning and the Dollar Sign signifies the end of the expression.

### Quantifiers

There are two quanitfiers are plus symbol(+) and curly brackets({ 2, 6 }). The "+" symbol means it'll joins two different things together. In this example it joins the first part of the email and the second half(everything after the @ sign). The curly brackets is a range of characters, so its between 2 and 6 in this case.

### Character Classes

The character class in this expression is "\d" which means to match any Arabic numeral digit from [0-9].

### Grouping and Capturing

There are 3 different capturing groups which you can see from the () around the expression. The first one is " [a-z0-9_\.-]+ ". The second one is " [\da-z\.-]+ ". The third one " [a-z\.]{2,6} ". 

### Bracket Expressions

The square brackets represent a range of charcters that we must include. Some examples of are [a-z] , [0-9] , [_\.-]. The first part of the expression is asking for a letter from a-z, a number from 0-9 and lastly a special character. 

## Author

You can check out my github https://github.com/HTapia7 