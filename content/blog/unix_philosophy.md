+++
title = "The Unix Philosophy"
author = ["Jethro Kuan"]
lastmod = 2018-12-22T11:11:34+08:00
tags = ["software-eng", "unix"]
draft = false
+++

In [The Art of Unix Programming](https://www.goodreads.com/book/show/104745.The%5FArt%5Fof%5FUNIX%5FProgramming), Ken Thompson was quoted to have
provided the following design rules:

-   Build modular programs
-   Write readable programs
-   Use composition
-   Separate mechanisms from policy
-   Write simple programs
-   Write small programs
-   Write transparent programs
-   Write robust programs
-   Make data complicated when required, not the program
-   Build on potential users' expected knowledge
-   Avoid unnecessary output
-   Write programs which fail in a way easy to diagnose
-   Value developer time over machine time
-   Write abstract programs that generate code instead of writing code by hand
-   Prototype software before polishing it
-   Write flexible and open programs
-   Make the program and protocols extensible

Particularly fascinating was the point on separating mechanisms from
policy. The argument is that mechanisms don't evolve as quickly as
policies, hence coupling the two would make it difficult to improve
upon the software without breaking the mechanism. Eric gave the
example of X, and the survival of X was attributed to its mechanisms
(the raster operations) being separated from the GUI implementations,
which had been phased out multiple times.