---
layout: post
title: Sketching redesigns
author: Minh Nguyen
---
I've decided today to go ahead with my last post on throwing everything out, and replacing everything with Jekyll. However, before I go ahead and start writing into the code, I need to come up with how it will appear to the user.

##Things to conform to.
For the sake of keeping things rather consistent (not fully), I do need to set some sort of guideline as to how I'll be designing this.

###Fluid layout
The sites in question should be able to be used by all manners of web browsers, including mobile devices, so they should be optimised for access with any device. Images that are placed in these fluid layouts should be able to scale up and down depending on the size of the content.

##The Sketchy Stuff
A few days ago, I came up with a couple of sketches to formulate my design for two sites:

- [My main portfolio site](/log/img/2012/02/17/portfolio-before.png) and...
- [My webcomic site](/log/img/2012/02/17/webcomic-before.png).

For the former, it may be necessary in the long term, whereas the webcomic site requires immediate attention, due to being only in partial progress in design. It's probably one of the more weaker points of my work.

###The Webcomic
![Sketch of my new webcomic's site](/log/img/2012/02/17/webcomic-sketch.png)

For this sketch, I took some influence from another webcomic's site, [Lackadaisy](http://lackadaisy.foxprints.com) in with it's excellent layout, particularly the front page with two column layout. News as it updates shows up on the left column, and the second column will contain a thumbnail of the current comic, as well as some miscellaneous content, like ongoing themes (which will be a main driving force in said comic).

Jekyll should be able to distinguish and display articles appropriately with the use of YAML tags, either comic or news respectively. I suppose I could do the same with other pages for sorting.

###The Portfolio
![The sketch for my portfolio site](/log/img/2012/02/17/portfolio-sketch.png)

This site needed additonal inspiration in order to come up with the layout that I've done here. As such, it is only an early draft and may be changed over time. The singular column allows for (what I believe to be) a good load of focus on the entries themselves. Dividers will be used within to divide as such the entries, meaning that I do not have to rely upon the &lt;table&gt; tag, which is really only meant for tabular data.
