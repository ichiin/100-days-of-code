# #100DaysOfCode Log - Round 1 - ichiin

The log of my #100DaysOfCode challenge. Started on [July 21, Sunday, 2019].

## Log

### R1D1 
Working on my Blog app. Adding a blog post to the database doesn't work if I paste an image in the Quill editor.
Looks like an issue with the number of characters in the request. Going over 7073 in the request URL length triggers the bug.


### R1D2
Got help from my coworker, issue was related to the Content-Type header attribute. Setting it on application/json fixed it on Postman. Need to look into this tomorrow to really understand what was happening.
Fun Fact : the application worked out of the box on Linux...


### R1D3
Light work today, implemented the postman solution into the backend. Previously, the post data was sent in the req.query which couldn't hold long string
Passing the parameter in the body makes it work like a charm !

### R1D4

Fixed a bug which disabled Material UI Grid system. Somehow I added a div element right BEFORE the first container which messed everything up.
Cleaned up unused files, imports and formated the code nicely.
Tomorrow I need to clean and rethink the database conception as well as start thinking about a minimalist layout.

### R1D5

Redid the database conception. Not sure if I should add a different collection for the comments or add it in the post collection.
Still going with mongo for learning purposes. Starting making the back end RESTful.

### R1D6

Started a minimalist home page design on Figma.

### R1D7

Added headers and replaced some elements on Figma

### R1D8

After changes requests don't work anymore, linked to the way I passed arguments in constructor (passing variables directly
instead of passing full body). Now, addMail works but it returns 400 in Postman.


