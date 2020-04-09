# Some notes on coding standards

To write a clean and readable code is a hard task. However this should not be 
a painful experience. I see coding as writing a story. While writing scripts and 
more complex pieces of software we are doing both programming a 
machine and telling a story to at least one person, which is your future self reading that piece of code.     

Here are some notes on coding standards and styling guides for data science programming languages. 

## Some definitions: Letter cases

### Camel forms
#### camelCase  

Here there are no spaces between words and the first letter is lower-case.
Each word after the first begins with a capitalized letter.

**Examples**: `camelFormVariable`, `secondMethod`

<img src="https://upload.wikimedia.org/wikipedia/commons/c/c8/CamelCase_new.svg"  width="120" height="120" title="cameCase" alt ="cameCase">

<small>Source: wikipedia</small>

#### PascalCase

Subset of camel form where the first letter is capitalized. 

**Example**: `AnotherCamelFormVariable`

### Underscore_united
#### snake_case 
Verb and nouns are glued by underscores. 

**Example**: `underscore_defined_function()`

#### SCREAMING_CASE
Common case of underscored variables with all caps letters. 

**Examples**: `THIRD_VARIABLE`, `ITERATOR` 

### Hyphen_united

#### skewer-case a.k.a. kebap-case

Each word is separated by a hyphen.

**Examples**: `this-is-a-variable` 

### Summary

Type           | Example             | Usage                                                     |
---------------|---------------------|-----------------------------------------------------------|
camel case     | `exampleVariable`   | In general for R, JSON, JavaScript variables              | 
pascal case    | `ExampleVariable`   | Classes in Java, Classes and Modules in Python            |
snake case     | `example_variable`  | Variables and methods in Python                           |
screaming case | `EXAMPLE_VARIABLE`  | Bash variables, constants in Python, JavaScript           |
kebap case     | `example-variable`  | CSS                                                       |

## Style guides

### Python

- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

### R
- [Google's R style code](https://google.github.io/styleguide/Rguide.html)
- [Hadley Wickham's tidyverse style guide](https://style.tidyverse.org/)

### Bash 

- [Bash Style Guide and Coding Standard](https://lug.fh-swf.de/vim/vim-bash/StyleGuideShell.en.pdf)
- [Some `Bash` coding conventions and good practices](https://github.com/icy/bash-coding-style)

## Other sources
- [Bholben Naming Conventions](https://github.com/bholben/Naming-Conventions)
- [Coding with Corgis](https://medium.com/codewithcorgis/naming-conventions-with-corgis-8a567549c4bc)