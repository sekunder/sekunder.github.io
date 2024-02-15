---
title: "Example Curriculum"
permalink: /ug-curriculum
author_profile: false
---

To effectively engage in the research that I do, you will need to learn some of the following subjects/skills. Don't be intimidated! I am not expecting you learn everything on this list, and I am not expecting you learn it all at once. The goal for this list is to update it over time with links to relevant texts/tutorials, so this page can serve as a reference when you need to learn something new.

# Mathematics

* Probability theory and information theory
    * Random variables: meaning, expectation, moments
    * Joint distributions of random variables, including marginalization and conditioning
    * Entropy of a distribution
    * Using the max-entropy principle
* Graph theory
    * Basic terminology: vertex (or node), edge, walk, path, cycle, clique, ...
    * Adjacency matrices
    * Laplacian matrices
* Discrete math
    * the Boolean lattice and partially ordered sets in general
    * Mobius inversion
* Linear Algebra
    * Know what eigenvectors and eigenvalues are. Learn what they mean in a variety of contexts; for example: in PCA, in multivariate Gaussian distributions, in graph adjacency and Laplacian matrices
    * Just keep learning linear algebra, forever; you will never regret learning more linear algebra
* Calculus, especially multivariable/vector calculus
    * Be able to compute the gradient of a complicated-looking function (e.g. the loglikelihood function)
    * Have some intuition for what derivatives are (they let you do linear approximations of functions; remember how I said you'll never regret learning more linear algebra)



# Programming

## Languages
Most of my work is done in Python or Julia
* `Python` is one of the most popular languages in use right now. There are extensive packages written for it to accomplish just about anything you want to do.
* `Julia` is a more recent language that attempts to bridge the gap between the ease of use of Python and the performance of lower-level language like C. One major reason I like it is the design of the type system.

## The Command Line
Learn to use the Linux command line. If you end up needing to use high-performance computing resources (such as the Holland Computing Center), this is basically your only way to interface with such systems. Also, learning to use the commandline will make you cooler and more handsome.

## Misc
* Use git. Ideally, learn to use it from the command line, but use git. Whenever you've got working code, make a commit. When you're about to make major changes to your code, commit, then checkout a new branch so you can scrap it if things completely fall apart.
* Also, use github, so you can back up your work and share it with others
* Document your code. This includes writing docstrings for functions/modules/classes, as well as inline comments to explain algorithms
* Test your code. This includes learning to write effective test scripts as well as learning to use automated testing tools that integrate with github