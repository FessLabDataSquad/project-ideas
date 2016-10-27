# project-ideas
looking for something to do?

This file will include ideas for mini-projects that would improve my code and be useful learning for RAs with various skill levels. (Right now these are all kind of general ideas, but I could include specific ideas for specific research projects that need some coding task done.)


 1. Data Cleaning

Most of my cleaning work uses just base R. Packages like {tidyr} and {dplyr} would definitely improve efficiency. So a very broad project is to improve my code using these kinds of packages. This big task can be broken into smaller tasks, such as...


 (a) variable naming
 
 (b) assigning vectors their proper class (e.g. factor, integer, etc)
 
 (c) tidying in the formal sense
 
 Our 1st assignment is a cleaning project. At any point in time I probably have several of these.
 
 
 
 2. Format / Style
 
R is flexible -- there are many ways to do the same thing. It might be useful to have standard conventions. For example:
 
 (a) we'll use = instead of <- because the former is more common in other programming languages.
 
 (b) we'll avoid creating objects with a dot in the name and use the underscore instead (e.g. data_study1 instead of data.study1) because in many other languages dots in names create problems
 
 (c) should we always load packages at the top of the script? or is it better to load in the line just above when the package is needed? perhaps the latter is useful while the code is in development, but moving to the top is a polishing step?
 
 
 3. Data visualization
 
The ggplot2 package can create pretty spectucular figures. Improving aesthetics or code efficiency could be useful.
 
 
