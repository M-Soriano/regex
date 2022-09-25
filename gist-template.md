# Title (Regex Tutorial)

Introductory paragraph (This is a tutorial in understanding Regex)

## Summary
Regex or Regular expression is a special text string  for describing a search pattern. For example lets say you want to find a string(word) that has the  least one letter n in it. You can use Regex with n+  to find all strings(words) with n. Or if you want to find all strings(words) without that letter n, you should use n*. 
This Regex is useful for operation like find, find and replace, as well as, input validation.




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

Anchors  ensure that a reqex matches a string at  a pecific place. Position little before or after a character.
^ = this matchs the before 
Example  ^J  would match Joke 
'$' = this matches after
Exmaple 't$' = would match out

### Quantifiers'
Quantifiers indicate the number of characters or expression to match
"*"  =Matches zero or more times
"+"  =Matches one or more times


### OR Operator
OR operator allows you to make a regular expression pattern to match one  out of  a set of choices.
You can match to the left or right
Example 
(t|T) this will match either T or t

### Character Classes
Character class allows you to specify a set of character that you want to match.
\d match a single digit or character from 0-9
\D match a non digit


### Flags
A flag is an optional parameter to a regex that changes the behavior of searching
flag i makes the expression search case insensity
so A and a will be seen
Example

const str ="regex148"

str.match(/E/i)  //["e"]



### Grouping and Capturing

Grouping and Capturing  are a way to treat multiple characters as a single unit.

### Bracket Expressions
A bracket expresssion represent a list of characters enclosed by [].

### Greedy and Lazy Match
input /bird/cat/

Greedy = will match longest possible string.
^/.*/  =  /bird/cat/

Lazy Match = will matfch shortest possible string
^/.*?/  =  /bird/

### Boundaries
There are three position to qualify boundaries
before the first character in the string.

After the last character in the string

Between two character in the string


### Back-references
back reference is a regualr expression identifies  a previously matched group and looks for exactly the same text again


### Look-ahead and Look-behind
Look-ahead and look behind refers to finding only those matches for a pattern that are followed or preceded by another pattern.Together refeed to as lookaround.
(?=foo)  Asserts that what immediately follows the current postion is the string foo
(?<=foo) Asserts that what immediatley precedes the current postion is the string isfoo 

## Author

Author Miguel Soriano

github profile https://github.com/M-Soriano


