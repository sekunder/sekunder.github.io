---
title: "Example Curriculum"
permalink: /ug-curriculum
author_profile: false
---

To effectively engage in the research that I do, you will need to learn some of the following subjects/skills. Don't be intimidated! I am not expecting you learn everything on this list, and I am not expecting you learn it all at once. The goal for this list is to update it over time with links to relevant texts/tutorials, so this page can serve as a reference when you need to learn something new.

# Mathematics

* Linear Algebra
    * Know what eigenvectors and eigenvalues are. Learn what they mean in a variety of contexts; for example: in PCA, in multivariate Gaussian distributions, in graph adjacency and Laplacian matrices, in multivariable calculus, in differential equations, in markov chains, ...
    * Just keep learning linear algebra, forever; you will never regret learning more linear algebra
* Probability theory and information theory
    * Random variables: expectation, moments
    * Joint distributions of random variables, including marginalization and conditioning
    * Entropy of a distribution and using the max-entropy principle
    * Markov chains
* Graph theory
    * Basic terminology: vertex (or node), edge, walk, path, cycle, clique, ...
    * Adjacency matrices
    * Laplacian matrices
* Discrete math
    * the Boolean lattice and partially ordered sets in general
    * Mobius inversion
* Calculus, especially multivariable/vector calculus
    * Be able to compute the gradient of a complicated-looking function (e.g. the loglikelihood function)
    * Have some intuition for what derivatives are (they let you do linear approximations of functions; remember how I said you'll never regret learning more linear algebra)

# Computational Neuroscience, Artificial Intelligence, and Machine Learning

* The McCulloch-Pitts model of the neuron
* Perceptron
* Hopfield Networks, Ising Models, Boltzmann Machines


# Programming

Here is a short [start up guide](/ug-programming) to help you get things set up to do computational neuroscience research.
I recommend using something like [VSCode](https://code.visualstudio.com/) to write scripts and notebooks.

## Languages
Most of my work is done in Python or Julia
* [`Python`](https://www.python.org/) is one of the most popular languages in use right now. There are extensive packages written for it to accomplish just about anything you want to do. It's free!
* [`Julia`](https://julialang.org/) is a more recent language that attempts to bridge the gap between the ease of use of Python and the performance of lower-level language like C. One major reason I like it is the design of the type system. It's free!
* [MATLAB](https://www.mathworks.com/products/matlab.html) is a proprietary programming environment with lots of nice features for doing matrix manipulations and lots of other things. It does cost money, but if you have a Creighton email address you should be able to get it for free.

## The Command Line
Learn to use the Linux command line. If you end up needing to use high-performance computing resources (such as the Holland Computing Center), this is basically your only way to interface with such systems. Also, learning to use the commandline will make you cooler and more handsome.

While you're at it, learn a little about the ["Unix philsophy"](https://en.wikipedia.org/wiki/Unix_philosophy) as an approach to writing programs (or parts of programs, e.g. the functions that you will use).

## Misc
* Use [git](https://git-scm.com/book/en/v2). Ideally, learn to use it from the command line, but use git. Whenever you've got working code, make a commit. When you're about to make major changes to your code, commit, then checkout a new branch so you can scrap it if things completely fall apart.
* Also, use [github](https://github.com/), so you can back up your work and share it with others
* Document your code. This includes writing docstrings for functions/modules/classes, as well as inline comments to explain algorithms
* Test your code. This includes learning to write effective test scripts as well as learning to use automated testing tools (e.g. those that integrate with github)