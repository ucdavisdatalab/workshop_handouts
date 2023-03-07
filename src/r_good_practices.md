# R Good Practices

This document is a description of good practices when programming in R.

## Formatting

* Put spaces around operators, after commas
* Indent blocks

## Clarity

* Break code into paragraphs
* Write functions
* Write loop bodies as functions
* Don't use `== TRUE` and `== FALSE`
* Don't use global variables
* Don't use explicit indexes in apply functions

## Efficiency

* Use variables instead of repeated calls
* Prioritize: vectorization > apply >= for > while > recursion
* Put as little as possible inside of loops
* Use as few iterations as possible
* Preallocate memory for loops

## References

*   Burns, P (2011). _The R Inferno_. URL
    <http://www.burns-stat.com/documents/books/the-r-inferno/>

*   Matloff, N (2011). _The Art of R Programming_. No Starch Press, San
    Francisco, CA.

*   R Core Team (2017). _R: A Language and Environment for Statistical
    Computing_. Vienna, Austria. URL <https://www.r-project.org/>
