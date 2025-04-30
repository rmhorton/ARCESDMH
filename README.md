# An R Companion to "[Evidence Synthesis for Decision Making in Healthcare](https://onlinelibrary.wiley.com/doi/book/10.1002/9781119942986)"

This is a collection of RMarkdown documents that run the original WinBUGs code from the book in JAGS from R.

STATUS: The following chapters contain code examples that are not yet working in JAGS:

* Chapter_10: All the files from the Supplemental Materials compile and execute; some have not been checked against the results in the book or in WinBUGS. Some examples from the book have been typed in but not yet run. 



Code that needed to be tweaked to run in JAGS:

* Chapter_04: There were 'Attempt to redefine node' errors in a couple of models. I moved the offending lines into data blocks, as recommended on [stackoverflow](https://stackoverflow.com/questions/78502051/how-to-convert-winbugs-code-into-jags-r-code).
* Chapter_09: `rank` function; multi-dimensional data reformatted as list of matrixes.
* Chapter_11: 'Attempt to redefine node' errors solved with data blocks.
* Chapter 12: `ranked` function.
* Chapter_10: Attempt to redefine node; Invalid parent values: Most of these issues are from 3d arrays in R being indexed differently than in JAGS. Divide by zero errors were worked around by adding a vanishingly small quantity to the denominator.
