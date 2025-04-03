# An R Companion to "[Evidence Synthesis for Decision Making in Healthcare](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119942986)"

This is a collection of RMarkdown documents that run the original WinBUGs code from the book in JAGS from R.

STATUS: The following chapters contain code examples that are not yet working in JAGS:

* Chapter_10: Attempt to redefine node; Invalid parent values



Code that needed to be tweaked to run in JAGS:

* Chapter_04: There were 'Attempt to redefine node' errors in a couple of models. I moved the offending lines into data blocks, as recommended on [stackoverflow](https://stackoverflow.com/questions/78502051/how-to-convert-winbugs-code-into-jags-r-code).
* Chapter_09: `rank` function; multi-dimensional data reformatted as list of matrixes.
* Chapter_11: 'Attempt to redefine node' errors solved with data blocks.
* Chapter 12: `ranked` function.

