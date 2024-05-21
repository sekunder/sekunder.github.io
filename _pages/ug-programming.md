---
title: "Programming Startup Guide"
permalink: /ug-programming
author_profile: false
---

This page is meant to serve as a sort of a start-up guide; what programs you should download and how you should configure your computer to dive in to computaional neuroscience research. This is far from comprehensive; I will try to keep this somewhat up to date but you should feel free to make your own contributions via [github pull requests](https://github.com/sekunder/sekunder.github.io).

# Setting the stage

Programming is a skill that can be developed with dedicated time and practice. Programming blends two difficult cognitive tasks: (1) abstract, high-level problem solving requiring you to conceptualize several interrelated moving pieces at once and (2) writing detailed, precise instructions that will be inrepreted literally by the computer. If you have never programmed before, I recommend starting by learning a single programming language ([python](https://docs.python.org/3/tutorial/index.html) is not a bad one) to start, and focus on learning the concepts, such as variables and types, statements, control flow, that sort of thing. In addition, get used to reading the docs and googling error messages. Switching from one language to another once you are already familiar with programming concepts is usually not too difficult.

The best way to learn to program is to program. Think of a task you would like to automate, or a problem you would like to solve, and program it. You'll find that even the "simple" things require a lot more effort than you first expect, and it is only through experience that you will learn how to do that sort of thing quickly.

# Your programming environment

I recommend using [VSCode](https://code.visualstudio.com/) to write scripts and notebooks. Other good text editors include [sublime text](https://www.sublimetext.com/) and [notepad++](https://notepad-plus-plus.org/) (windows only).

**Learn to use the unix command line.** On mac, this is the Terminal app. On Windows, you've got [powershell](https://learn.microsoft.com/en-us/powershell/), which is a poor substitute but is good enough. If you're using linux you probably know more about your computer than I do.
<!-- On Windows, I think you're best served by installing [powershell](https://learn.microsoft.com/en-us/powershell/) to get something closer to a linux/unix command line. -->

Learn to use [`git`](https://git-scm.com/) and [github](https://github.com/) (or other online repositories). Version control software is immensely useful -- it lets you create remote backups (that is, you can store a copy of your code on a remote server, such as github) but more importantly it lets you create a _version history_, that is, you can save a copy of your code when it works, and then if you break it you can easily revert to the working version.

# Python

One of the advantages of python is, as it is very popular, there are packages to do just about anything you need to do. For example, the `numpy` package lets you work with arrays and do linear algebra and `matplotlib` lets you make plots. To use them, you use the `import` command

```py
import numpy as np  # the "as" means that you can type np.thing instead of numpy.thing. Saves some typing.
import matplotlib.pyplot as plt

xs = np.arange(10)  # x is the array of values [0, 1, ..., 9]
ys = xs ** 2  # square each entry of the array x

plt.plot(xs, ys)  # plot the x,y pairs, connected by lines.
```

But... how do you actually get these packages on your computer? From the commandline, you can use `pip` (which stands for something like package installer for python). But you can save yourself a little time by first installing [`conda`](https://conda.io/projects/conda/en/latest/user-guide/install/index.html), which will automatically install a bunch of those packages for you.



<!-- ## Scripts, Notebooks, Packages, Modules... what??

A lot of terminology gets thrown around when it comes to programming, and you will gradually learn it with experience. Here's a bare minimum to get you started:
* Interpreted languages vs. compiled languages: You will most likely start programming with an interpreted language like python or julia, as opposed to a compiled language like Java or C. The difference is that an interpreted language can be 
* A notebook  -->