R is flexible -- there are many ways to do the same thing.

[A] It is useful to have standard conventions. For example:
- use = instead of <- because the former is more common in other programming languages. 
- avoid creating objects with a dot in the name and use the underscore instead (e.g. data_study1 instead of data.study1) because in many other languages dots in names create problems 
- should we always load packages at the top of the script? or is it better to load in the line just above when the package is needed? perhaps the latter is useful while the code is in development, but moving to the top is a polishing step?
- no "magic numbers" -- set variables (e.g. in reverse-scoring lines: SCALE_REVERSAL_VALUE = 8)

[B] Pretty much any code our team is working on could be made more efficient, often (but not always) with specialized packages.



Specific projects:

- Stylize the script for a paper about Disgust and Risk-Taking:
https://github.com/FessLabDataSquad/disgust-style

- Coming soon: Styling the script for a paper about elevation

- Create a repository specifically devoted to establishing our style conventions, including why and how.


