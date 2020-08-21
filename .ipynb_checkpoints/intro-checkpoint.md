# Note on Introduction 
## Markdown

Markdown is:

* a text formatting syntax aimed at making writing for the internet easier. 
* a way to style text on the web.

I personally use it for making notes. Some people use it to write webpage, technical documents, or even email messages. <br> 
Markdown files can be converted into HTML, PDF, Word, etc. <br>
For example, in the folder of _applied-economics_, there is a **README.md** file.

The basic syntax include:

* plain text, with italic and bold 
* different level of headers
* links
* images
* blockquotes
* lists
* formatting paragraph

You can learn some basic markdown syntax [here](https://www.markdowntutorial.com). This only take you less than 20 minutes.<br>
Further more, there are online editors that combine markdown and LaTex so you can write math in it, too. <br>
For example, [Typora](https://typora.io) or [Upmath](https://upmath.me).<br>
This may be helpful when you are going to write assignments.

## GitHub and Git

In the first assignment, you are asked to create a folder on the server `applied-economics` that contains the course material for the python part. To do this, you _clone_ the _repository_ to your own jupyter lab by running:

> `%%bash`
>
> `git clone https://github.com/janboone/applied-economics`

This _repository_ exactly locates on GitHub, specifically, this [webpage](https://github.com/janboone/applied-economics).

### GitHub

GitHub is a platform to store and share your code with others. It is useful for version control and collaboration.<br>
For the collaboration feature, we will be using GitHub for questions (_creating new issues_) and uploading your final assignment.<br>
For the version control part, althought the benefit of it is not that relevant for this course, it is useful for developers.

### Git

To utilize **GitHub** for version control, you need to learn **Git**.<br>
To avoid creating too much confusion, I provide a simple example here:

> Consider that you have clone the _repository_ `applied-economics` last week. <br>
> Today, you notice that the professor made a change in his repository and you would like to keep everything up to date.<br>
> Then, you can run:<br>
> `%%bash` <br>
> `cd ~/applied-economics` <br>
> `git pull`

The first line here helps us to go to the directory (folder) that we want to update. <br>
The second line here fetchs from and integrates with another repository. <br>

Only if you are interested, you can check this introdoctory class on [Datacamp](https://learn.datacamp.com/courses/introduction-to-git).
