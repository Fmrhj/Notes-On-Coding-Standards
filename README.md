# Short notes on naming standards

Here are some notes on naming standards and styling guides for programming languages. 

## Letter cases

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

Type           | Example             | Usage                                                                                             |
---------------|---------------------|---------------------------------------------------------------------------------------------------|
camel case     | `exampleVariable`   | In general for: **Go** variables (and non-exportable methods), **JavaScript** variables, **R**, **JSON** keys,           |
pascal case    | `ExampleVariable`   | Classes in **Java**, **C#**, Classes and Modules in **Python**, **Go** exportable methods, **Terraform** Definitions        |
snake case     | `example_variable`  | Variables and methods in **Python**, and **C/C++**                                                        |
screaming case | `EXAMPLE_VARIABLE`  | **Bash** variables, almost all constants e.g.: **Python**, **JavaScript**, **C/C++**; **env. variables**, **SQL**                   |
kebap case     | `example-variable`  | **CSS**, **git repos**, cloud and container resources, e.g. [**K8s** deployments](https://medium.com/faun/kubernetes-pod-naming-convention-78272fcc53ed) e.g. [Azure resource groups](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming), [GCP](https://stepan.wtf/cloud-naming-convention/) projects, etc.!                                                           |

## Short references

### C

- [Recommended C Style](https://www.doc.ic.ac.uk/lab/cplus/cstyle.html)

### Go 

- [Go Lint](https://github.com/golang/lint)

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
