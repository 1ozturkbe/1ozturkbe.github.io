---
layout: post
title: Global optimization paper submitted to OR and available on arXiv!
date: 15/02/2022
post_url: 2022-02-15-octhagonarxiv
categories: [blog, research, phd, global, optimization]
---

Now that **Global Optimization via Optimal Decision Trees** has been submitted to *Operations Research*, I am glad to also share a preprint [available from arXiv](https://arxiv.org/abs/2202.06017). 
Here is the abstract:

*The global optimization literature places large emphasis on reducing intractable optimization problems into more tractable structured optimization forms. In order to achieve this goal, many existing methods are restricted to optimization over explicit constraints and objectives that use a subset of possible mathematical primitives. These are limiting in real-world contexts where more general explicit and black box constraints appear. Leveraging the dramatic speed improvements in mixed-integer optimization (MIO) and recent research in machine learning, we propose a new method to learn MIO-compatible approximations of global optimization problems using optimal decision trees with hyperplanes (OCT-Hs). This constraint learning approach only requires a bounded variable domain, and can address both explicit and inexplicit constraints. We solve the MIO approximation efficiently to find a near-optimal, near-feasible solution to the global optimization problem. We further improve the solution using a series of projected gradient descent iterations. We test the method on a number of numerical benchmarks from the literature as well as real-world design problems, demonstrating its promise in finding global optima efficiently.*

I have also released some early-stage documentation for the [Julia implementation of OCTHaGOn](https://github.com/1ozturkbe/OCTHaGOn.jl), available [here](https://1ozturkbe.github.io/OCTHaGOn.jl/). More will come soon!

Berk 
