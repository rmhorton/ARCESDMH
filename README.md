# An R Companion to "[Evidence Synthesis for Decision Making in Healthcare](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119942986)"

This is a collection of RMarkdown documents that run the original WinBUGs code from the book in JAGS from R.

STATUS: The following chapters contain code examples that are not yet working in JAGS:

* Chapter_04: Attempt to redefine node
* Chapter_10: Attempt to redefine node; Invalid parent values
* Chapter_11: Attempt to redefine node


Code that needed to be tweaked to run in JAGS:

* Chapter_09: `rank` function; multi-dimensional data reformatted as list of matrixes.
* Chapter 12: `ranked` function.
