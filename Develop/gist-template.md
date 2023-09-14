# Regex Tutorial - Matching an Email

Introductory paragraph (replace this with your text)

This tutorial will go over the use of regex, commonly known as Regular Expression, in regards to using it to match to emails with an expression.  The purpose of matching and validating emails becomes extremely useful when using applications such as Node and/or MongoDB.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

The regex will utlize the following code to identify patterns that are commonly used for emails and validation: `/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`. This tutorial will explain the components utilized with regex and how each section can validate and match with an email.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [Author](#author)

### Anchors

The anchors that are utilized for the start and end of the string are `^` and `$`, respectfully. The `^` is utilized to let the system know that it is the start of the string. This is the same for `$`, however it indicates the end of the string. A multiline, or `(m)` is not enabled with this regex, so it will end with a `$`.

### Quantifiers

One major quantifier would be the `+` operator. This is a major component for this particular regex because it connectes the user's email name with their service as well as the `.com` portion of their overall email. A way to view this would be [User's Name]`+`[email service (like google, yahoo, etc)]`+``.com`. Another quantifier would be `{2,6}` which allows a range of 2 to 6 characters to match with the character set `[a-z\.]`.

### Grouping Constructs

There are three components for grouping an email. The first will utlize `([a-z0-9_\.-]+)` which will match with the User's Name they chose for their email. The second will use `([\da-z\.-]+)`, this will match which email service that is used for the User's choice of service. The last group will utilize `([a-z\.]{2,6})`, which captures the `.com`.

### Bracket Expressions



### Character Classes

The character class that is used within this expression is `\d`. It matches a single character with the digit range of 0 to 9. It will only match with a single digit however, anything past 9 will not register.

## Common Regex Component



## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)

I am an up and coming coder that is learning more and more about this diverse landscape. If you would like to check out my projects please follow this link to view my Github profile: https://github.com/StygianTanuki