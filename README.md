# project-ideas
looking for something to do?

This repo includes ideas for mini-projects that would improve FessLab code and would be useful learning exercises for RAs of various skill levels. Many are general ideas, but some are more focused and we can always talk about how to add focus to any of the general ideas.

#1. Data Cleaning

Most of my cleaning work uses just base R. Packages like {tidyr} and {dplyr} would definitely improve efficiency. So a very broad project is to improve my code using these kinds of packages. This big task can be broken into smaller tasks, such as...


 (a) variable naming: typically, source files have variables in columns, with some names on the first row, but often those names are too long, too short, unclear (e.g. "d1"). usually we want the final variables to be reasonably short (one or two words) and it should be kinda clear.
 
 (b) assigning vectors their proper class (e.g. factor, integer, etc)
 
 (c) tidying in the formal sense
 
 Specific projects:
 -  Assignment 1  https://github.com/FessLabDataSquad/Assignment1-CleanTrust
 -  Free Response Coding Data -- some of our lab members will be reading free responses and coding them (e.g. rating how "helpful" the response was on some quantitative scale). 

#2. Format / Style
 
R is flexible -- there are many ways to do the same thing. 

(a) It might be useful to have standard conventions. For example:
 
 (i) we'll use = instead of <- because the former is more common in other programming languages.
 (ii) we'll avoid creating objects with a dot in the name and use the underscore instead (e.g. data_study1 instead of data.study1) because in many other languages dots in names create problems
 (iii) should we always load packages at the top of the script? or is it better to load in the line just above when the package is needed? perhaps the latter is useful while the code is in development, but moving to the top is a polishing step?
 
 (b) Pretty much any code our team is working on could be made more efficient. 
 
 Specific project:
 - The elevation cleaning code involved reverse-scoring scale items. Current code uses a specific constant (8) over and over again, because this is a 7-point point likert scale, so to reverse it you substract the value from 8. But, hard-coding constants is a bad idea in general (eventually we can elaborate on why) so it would be better to set a variable (e.g. SCALE_REVERSAL_VALUE = 8) and recode accordingly. So, that code is included in the Assignment1 repo -- someone could fork it and clean it up.


#3. Data visualization
 
The ggplot2 package can create pretty spectucular figures. Improving aesthetics or code efficiency could be useful.
 
#4. Are we using GitHub functionality? What could we do better?
 
 (a) should this document be a wiki or something else?
 (b) are the projects well-organized?
 (c) are ideas and conversations too scattered around?
