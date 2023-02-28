Fast forward merges are where the branch being merged into has not had any commits and the branch being merched is a few commits ahead. 
This leads to the branch being merged into, in this case the develop branch, to being instantly and easily merged into.

To make a conflict, we changed the text of the first header. This guarantees a conflict because there is a difference in an already existing commit text.
To guarantee no conflict, we added a new header tag at the end of the html file. This is new and doesn't coincide with anything in the past commits.