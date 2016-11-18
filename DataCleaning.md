By "data cleaning" we mean the process of converting raw data into a format convenient for analysis. Most FessLab cleaning scripts currently use base R. Packages like {tidyr} and {dplyr} would definitely improve efficiency. So, a very broad project is to improve FessLab code using these kinds of packages. 


This big task can be broken into smaller tasks, such as...

 (a) variable naming: typically, source files have variables in columns, with some names on the first row, but often those names are too long, too short, unclear (e.g. "d1"). usually we want the final variables to be reasonably short (one or two words) but with some clarity about their meaning. We've started to use a 2-vector object with the short names and the full items.
 
 (b) assigning vectors their proper class (e.g. factor, integer, etc)
 
 (c) tidying in the formal sense
 {tidyr} written by Hadley Wickham, see http://vita.had.co.nz/papers/tidy-data.pdf
 
 
 Specific projects:
 -  Assignment 1  https://github.com/FessLabDataSquad/Assignment1-CleanTrust
 
 -  Free Response Coding Data -- Lab members currently reading free responses and coding them (e.g. rating how "helpful" the response was on some quantitative scale). 
 
 - Coming soon: Assignment 2 (Elevation)
