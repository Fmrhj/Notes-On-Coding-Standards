# Short notes on naming standards

<!-- toc -->
- [Variable naming](#variable-naming)
- [Comment style](#comment-style)
- [References](#references)

<!-- tocstop -->

Here are some notes on naming standards and styling guides for programming languages.

## Variable naming

### Camel forms

#### camelCase  

Here there are no spaces between words and the first letter is lower-case.
Each word after the first begins with a capitalized letter.

**Examples**: `camelFormVariable`, `secondMethod`

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

## Documenting and comemnt style

### R

Comment with `#` and use lines to break up the script. This is specially helfpul for [R Markdown](https://rmarkdown.rstudio.com/).

```R
# Load data -----

# Plot data -----
```

### Python

The [PEP 257](https://www.python.org/dev/peps/pep-0257/) proposes docstrings conventions. Since docstrings become the `__doc__` special object attribute, it conveys so much information for larger codebases. Here is an example for the [reStructuredText format](https://www.python.org/dev/peps/pep-0287/):

```python
def special_method():
    """
    Some description about the method/class
    :param param1: example first parameter
    :param param2: example second parameter
    :returns: this is the returned value
    :raises ValueError: if an exception is raised in a special case
    """
```

Personally, I prefer the [GoogleDoc style](https://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html) because it documents the types of the object related variables. This is useful since Python inclusion of type hints implemented by [PEP 484](https://www.python.org/dev/peps/pep-0484/).

Check out this [blog](http://daouzli.com/blog/docstring.html) for more information. Also this [stackoverflow](https://stackoverflow.com/a/24385103).

## Short references

### C - short references

- [Recommended C Style](https://www.doc.ic.ac.uk/lab/cplus/cstyle.html)

### Go - short references

- [Go Lint](https://github.com/golang/lint)

### Python -short references

- [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)

### R -short references

- [Google's R style code](https://google.github.io/styleguide/Rguide.html)
- [Hadley Wickham's tidyverse style guide](https://style.tidyverse.org/)

### Bash - short references

- [Bash Style Guide and Coding Standard](https://lug.fh-swf.de/vim/vim-bash/StyleGuideShell.en.pdf)
- [Some `Bash` coding conventions and good practices](https://github.com/icy/bash-coding-style)

## Other sources

- [Bholben Naming Conventions](https://github.com/bholben/Naming-Conventions)
- [Coding with Corgis](https://medium.com/codewithcorgis/naming-conventions-with-corgis-8a567549c4bc)
