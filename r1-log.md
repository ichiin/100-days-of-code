# #100DaysOfCode Log - Round 1 - ichiin

The log of my #100DaysOfCode challenge. Started on [July 21, Sunday, 2019].

## Log

### R1D1 
Working on my Blog app. Adding a blog post to the database doesn't work if I paste an image in the Quill editor.
Looks like an issue with the number of characters in the request. Going over 7073 in the request URL length triggers the bug.


### R1D2
Got help from my coworker, issue was related to the Content-Type header attribute. Setting it on application/json fixed it on Postman. Need to look into this tomorrow to really understand what was happening.
Fun Fact : the application worked out of the box on Linux...
