# project-ideas
looking for something to do?

This file will include ideas for mini-projects that would improve my code and be useful learning for RAs with various skill levels. Many are general ideas, but some are more focused and we can always talk about how to focus one of the general ideas.

#1. Data Cleaning

Most of my cleaning work uses just base R. Packages like {tidyr} and {dplyr} would definitely improve efficiency. So a very broad project is to improve my code using these kinds of packages. This big task can be broken into smaller tasks, such as...


 (a) variable naming
 
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


#3. Data visualization
 
The ggplot2 package can create pretty spectucular figures. Improving aesthetics or code efficiency could be useful.
 
#4. Are we using GitHub functionality? What could we do better?
 
 (a) should this document be a wiki or something else?
 (b) are the projects well-organized?
 (c) are ideas and conversations too scattered around?
